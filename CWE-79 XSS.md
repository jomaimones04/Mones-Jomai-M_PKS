A security vulnerability that allows attackers to inject malicious scripts into web pages viewed by others, often to steal data or hijack user sessions.

How XSS Work?

•	Attacker injects malicious script into a web app input or URL.

•	The app returns that untrusted input to other users without proper escaping/validation.

•	The victim’s browser executes the injected script, letting the attacker steal cookies, tokens, or perform actions as the user.

Types of XSS attacks

Reflected XSS (Non Persistent / Type 1)

Attacker sends a link or form that the server immediately echoes back and the victim’s browser executes. 

Stored XSS (Persistent / Type 2)

Malicious script is saved on the server (comments, profiles) and runs for every viewer. 

DOM Based XSS (Type 0)

Client side JavaScript writes attacker controlled data into the DOM unsafely no server echo involved.

uXSS (Universal XSS)

Browser or extension (engine) vulnerability lets an attacker run scripts across multiple sites/origins often a browser bug or extension exploit.

Self XSS

Social engineering: user is tricked into pasting malicious code into their browser console, which then runs in their session.
