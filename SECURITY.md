# Security Policy

## Supported Versions

ConvergioAI is in its early public release phase. Security updates will be applied to the latest version on the `main` branch.

| Version | Supported |
|:--------|:---------:|
| Latest (`main`) | Yes |
| Older releases | No |

## Reporting a Vulnerability

We take security seriously at ConvergioAI. If you discover a security vulnerability, please report it responsibly.

### How to Report

**Do not open a public GitHub issue for security vulnerabilities.**

Instead, please report vulnerabilities through one of these channels:

1. **GitHub Security Advisories (Preferred):** Use [GitHub's private vulnerability reporting](https://github.com/InstinctBits/convergioai/security/advisories/new) to submit a confidential report directly through this repository.

2. **Email:** Send details to **security@digitechnomads.com** with the subject line `[ConvergioAI Security]`.

### What to Include

- A clear description of the vulnerability
- Steps to reproduce the issue
- The potential impact or severity
- Any suggested fixes (optional but appreciated)

### What to Expect

| Step | Timeline |
|:-----|:---------|
| Acknowledgment of your report | Within 48 hours |
| Initial assessment and triage | Within 5 business days |
| Status update on the fix | Within 10 business days |
| Security patch released | Based on severity |

### Severity Response Times

| Severity | Response |
|:---------|:---------|
| **Critical** (RCE, auth bypass, data exposure) | Patch within 48 hours, immediate advisory |
| **High** (privilege escalation, injection) | Patch within 7 days |
| **Medium** (information disclosure, CSRF) | Patch within 30 days |
| **Low** (minor information leak, best practice) | Addressed in next release |

## Security Best Practices

When self-hosting ConvergioAI, follow these guidelines:

- **Never commit `.env` files** or expose secrets in source control
- **Use strong, unique values** for `BETTER_AUTH_SECRET`
- **Keep dependencies updated** — run `npm audit` regularly
- **Use HTTPS** in production for all API and frontend traffic
- **Restrict database access** — do not expose PostgreSQL to the public internet
- **Review API keys** — rotate Anthropic API keys periodically

## Scope

The following are **in scope** for security reports:

- Authentication and session management vulnerabilities
- API endpoint authorization bypasses
- SQL injection, XSS, CSRF, and other OWASP Top 10 issues
- Sensitive data exposure in API responses
- Dependency vulnerabilities with a known exploit

The following are **out of scope**:

- Vulnerabilities in third-party services (Anthropic API, Cal.com, Hostinger)
- Social engineering attacks
- Denial of service (DoS) attacks
- Issues in environments running unsupported or modified versions

## Recognition

We appreciate security researchers who help keep ConvergioAI safe. With your permission, we will acknowledge your contribution in the release notes of the security patch.

---

<table>
  <tr>
    <td align="center">
      <strong>ConvergioAI</strong> — Open-source AI-powered omnichannel CRM
      <br /><br />
      Built at <a href="https://github.com/InstinctBits">InstinctBits Labs</a> | Sponsored by <a href="https://digitechnomads.com">DigiTech Nomads</a>
      <br /><br />
      <a href="https://docs.digitechnomads.com">Documentation</a> · <a href="https://github.com/InstinctBits/convergioai">GitHub</a> · <a href="https://github.com/InstinctBits/convergioai/discussions">Discussions</a> · <a href="https://github.com/InstinctBits/convergioai/blob/main/LICENSE">MIT License</a>
      <br /><br />
      <sub>&copy; 2026 InstinctBits. All rights reserved.</sub>
    </td>
  </tr>
</table>
