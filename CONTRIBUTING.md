# Contributing to ConvergioAI

Thank you for your interest in contributing to ConvergioAI! This guide will help you get started.

## How to Contribute

### Reporting Bugs

Found a bug? Open an issue using the [Bug Report template](https://github.com/InstinctBits/convergioai/issues/new?template=bug_report.yml). Include:

- A clear, descriptive title
- Steps to reproduce the behavior
- Expected vs actual behavior
- Screenshots if applicable
- Your environment (OS, Node.js version, browser)

### Suggesting Features

Have an idea? Open an issue using the [Feature Request template](https://github.com/InstinctBits/convergioai/issues/new?template=feature_request.yml) or start a thread in [GitHub Discussions](https://github.com/InstinctBits/convergioai/discussions).

### Submitting Code

1. **Fork** the repository
2. **Create a branch** from `main` (`git checkout -b feat/your-feature`)
3. **Make your changes** — keep commits focused and descriptive
4. **Test your changes** — ensure nothing is broken
5. **Open a Pull Request** against `main` using the PR template

### Branch Naming

| Prefix | Purpose |
|:-------|:--------|
| `feat/` | New feature |
| `fix/` | Bug fix |
| `docs/` | Documentation only |
| `refactor/` | Code refactoring (no feature change) |
| `test/` | Adding or updating tests |

### Commit Messages

Follow the [Conventional Commits](https://www.conventionalcommits.org/) format:

```
feat: add brand logo upload endpoint
fix: resolve email tag parsing for support inbox
docs: update API endpoint reference
```

## Development Setup

> **Note:** ConvergioAI is in early public release. Full setup instructions will be published with Phase 1. For now, refer to the [documentation](https://docs.digitechnomads.com).

### Prerequisites

- Node.js 20+
- PostgreSQL 15+
- npm 10+

### Quick Start

```bash
git clone https://github.com/InstinctBits/convergioai.git
cd convergioai
cp .env.example .env    # Configure your environment
npm install
npm run dev:all         # Starts frontend + backend
```

## Code Style

- **TypeScript** for all source files
- **Named exports** (not default exports)
- **No Tailwind** — use custom CSS with Tabler dark theme variables
- **DOMPurify** required for any HTML rendering
- Keep changes focused — one feature or fix per PR

## Review Process

1. A maintainer will review your PR within 5 business days
2. Address any requested changes
3. Once approved, a maintainer will merge your PR

## Code of Conduct

By participating, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions?

Open a thread in [GitHub Discussions](https://github.com/InstinctBits/convergioai/discussions) — we're happy to help.

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
