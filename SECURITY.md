# Security policy

This policy applies to every repository of the Quire organisation that doesn't have a security policy of its own.

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues, discussions or pull requests.**

Report them privately, in either of these ways:

- **Through GitHub:** go to the **Security** tab of the affected repository, e.g. [quirecms/framework](https://github.com/quirecms/framework/security), and click **Report a vulnerability**.
- **By email:** write to [security@quirecms.com](mailto:security@quirecms.com).

Describe the issue. Include as much of the following as you can:

- the affected package (e.g. `quire/core`) and version or commit;
- the type of issue (e.g. SQL injection, cross-site scripting, authentication bypass);
- steps to reproduce, or a proof of concept;
- the impact, i.e. what an attacker could achieve.

Only the maintainers can see your report.

## What happens next

- We acknowledge your report within **3 working days**.
- We confirm or rule out the issue, and keep you updated while we work on a fix.
- We aim to release a fix within **90 days** of the report, sooner for critical issues.
- Once a fix is released, we publish a security advisory and credit you, unless you prefer to stay anonymous.

Please give us a reasonable chance to fix the issue before you disclose it publicly.

## Supported versions

Quire is in early development and hasn't had a stable release yet. Until 1.0, security fixes go only into the latest code on the `main` branch.
