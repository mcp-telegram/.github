# Security policy

This policy applies to every repository in the [mcp-telegram](https://github.com/mcp-telegram) organization that does not have its own `SECURITY.md`. The hosted service has a detailed threat model in [mcp-telegram-cloud/SECURITY.md](https://github.com/mcp-telegram/mcp-telegram-cloud/blob/main/SECURITY.md).

## Reporting a vulnerability

**Please do not open a public issue for security problems.**

Use one of these private channels:

- GitHub private vulnerability reporting: open the **Security** tab of the affected repository and select **Report a vulnerability** ([mcp-telegram](https://github.com/mcp-telegram/mcp-telegram/security/advisories/new), [mcp-telegram-cloud](https://github.com/mcp-telegram/mcp-telegram-cloud/security/advisories/new)).
- Email: **security@mcp-telegram.com**.

You can write in any language. Please include:

- what the problem is and what an attacker could do with it;
- steps to reproduce (a proof of concept helps but is not required);
- the affected version, commit or Docker tag.

We aim to acknowledge a report within 72 hours and to ship a fix or mitigation for high-severity issues within 14 days. We credit reporters in the release notes unless you prefer to stay anonymous.

## Supported versions

Only the latest release of each package receives security fixes: `@overpod/mcp-telegram` on npm and the `mcp-telegram-cloud` Docker image.
