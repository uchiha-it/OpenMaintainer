# Security Policy

OpenMaintainer is currently in pre-launch / proposal stage and is not ready for production use.

The project is expected to process untrusted repository content and may eventually execute repository code in isolated environments. Security is therefore a core design requirement.

Planned safeguards include:

- sandboxed execution;
- restricted credentials;
- no automatic secret access;
- explicit permission boundaries;
- resource limits;
- audit logs;
- human approval before consequential actions.

Please do not use pre-release versions with sensitive repositories or production credentials unless the relevant security controls have been implemented and independently reviewed.
