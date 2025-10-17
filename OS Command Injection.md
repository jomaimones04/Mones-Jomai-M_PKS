OS Command Injection

An attacker supplies input that gets executed as an operating system command by an application, allowing them to run arbitrary commands on the server.

Why it’s dangerous: 

full system compromise, data theft, service disruption.

Prevention:

Never pass raw user input to shell commands.

Use safe APIs (library functions).

Validate/whitelist input and escape/sanitize when necessary.

Run services with least privilege and use containers/isolated environments.

