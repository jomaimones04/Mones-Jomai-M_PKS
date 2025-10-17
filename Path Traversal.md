A vulnerability that allows attackers to access files and directories outside the intended folder by manipulating file paths

Impacts

Access to sensitive files, config leaks, remote code execution.

Preventing Directory Traversal

Validate and Sanitize User Input: Use an "accept known good" approach (allowlisting).

Use Allow Lists for File Access: Explicitly define allowed files or directories.

Avoid Using User Input Directly in File Paths: Construct file paths carefully.

Utilize Built-in Functions for Path Normalization: Neutralize traversal sequences.

Implement Access Control Measures: Apply the principle of least privilege.

Isolate Execution Environments: Confine the application to a limited file system.
