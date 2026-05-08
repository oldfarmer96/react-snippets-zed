# Contributing

Thank you for contributing to React Lain Snippets for Zed.

## Development Guidelines

- Keep snippet bodies simple and compatible with current Zed snippet behavior.
- Prefer portable placeholders (`$1`, `${1:default}`, `$0`).
- Avoid VS Code-only snippet transforms unless confirmed to work in Zed.

## How to Contribute

1. Fork the repository.
2. Create a feature branch from `main`.
3. Make focused changes.
4. Test snippets in Zed (`.tsx` and `.jsx` files).
5. Update `README.md` and `CHANGELOG.md` when behavior changes.
6. Open a Pull Request with a clear description.

## Reuse and Forks

This project is MIT licensed. You are free to copy, fork, modify, and redistribute it as long as the license notice is preserved.

## PR Checklist

- Snippets expand correctly with `Tab`.
- Snippet scope is correct for Zed (`tsx.json`, `javascript.json`).
- No invalid JSON.
- Docs/changelog updated.

## Commit Message Suggestion

Use concise messages that explain intent, for example:

- `fix: use javascript scope for JSX snippets in Zed`
- `feat: add react hook snippet shortcuts`
