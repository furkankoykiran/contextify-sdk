# Contributing to contextify-sdk

Thanks for your interest in contributing.

## Ground rules

1. Open an issue for non-trivial work before sending a PR. Small fixes (typos,
   bug fixes with clear repro) can go straight to PR.
2. One logical change per commit; commit messages use Conventional Commits
   (`type(scope): description`). Types: `feat`, `fix`, `refactor`, `docs`,
   `test`, `chore`.
3. **No AI/LLM attribution** in commits, PR bodies, issues, or reviews.

## Local dev

This repository is in **initial scaffolding** state. The real toolchain
(installer, build, tests) lands with the first feature release. Until then:

- File issues, discuss design, send small text-only PRs (docs, license).
- Larger code PRs will be reviewed once the package's first feature release
  has shipped.

## Code style

- Follow the language-native idioms (PEP 8 / Black for Python, Prettier /
  ESLint for TypeScript).
- Match existing patterns; do not introduce new abstractions without
  discussion.

## Tests

When the test harness lands, every PR must include tests for the changed
behavior. Until then, run any obvious smoke tests and describe them in the PR.

## Reporting bugs

Use the bug-report issue template. Include:

- What you were trying to do.
- What happened.
- What you expected to happen.
- A minimal reproduction.

## Security

See [`SECURITY.md`](SECURITY.md). Never paste raw secrets, tokens, or
provider keys into issues or PRs.

## License

By contributing you agree your contribution is licensed under the
repository's [`LICENSE`](LICENSE).
