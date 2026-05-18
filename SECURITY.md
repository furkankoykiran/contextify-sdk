# Security policy

## Reporting a vulnerability

Email **security@contextify.live** with a description, reproduction steps, and
any logs or screenshots. Please do not open public GitHub issues for security
reports.

We aim to acknowledge new reports within 3 business days. Confirmed
high-severity issues receive a fix or mitigation plan within 30 days.

## Scope

This repository (`contextify-sdk`) is part of the public surface of the
[Contextify](https://contextify.live) project. Reports relevant to this repo include:

- Code execution or sandbox escape via the SDK, hook adapter, MCP server, or
  example projects.
- Credential or secret leakage through any code path shipped here.
- Supply-chain compromise of dependencies pinned by this package.

Reports about the Contextify SaaS itself (account, billing, dashboard, API
tokens) should also be sent to **security@contextify.live**.

## Out of scope

- Theoretical issues without a reproduction.
- Dependency vulnerabilities for which no upstream fix is yet available.
- Social engineering and physical access scenarios.

## Disclosure

We follow coordinated disclosure. Reporters who follow this policy will be
credited in `CHANGELOG.md` unless they request otherwise.
