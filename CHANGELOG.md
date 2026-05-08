# Changelog

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog, and this project follows Semantic Versioning.

## [0.1.0] - 2026-05-08

### Added

- Added `snippets/javascript.json` to support JSX snippets in Zed.
- Added attribution note in `README.md` for inspiration source:
  - `https://github.com/shonebinu/zed-react-snippets`
- Added project documentation files:
  - `README.md`
  - `CONTRIBUTING.md`
  - `SECURITY.md`
  - `CODE_OF_CONDUCT.md`

### Changed

- Updated extension snippet registration to use `snippets/javascript.json` instead of `snippets/jsx.json`.
- Simplified snippet placeholders for better Zed compatibility:
  - Replaced `TM_FILENAME_BASE` usages.
  - Replaced regex transform in `useState` snippet.

### Removed

- Removed `snippets/jsx.json` (deprecated for Zed JSX scope).
