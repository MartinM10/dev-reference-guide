# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0](https://github.com/MartinM10/dev-reference-guide/compare/v1.1.0...v1.2.0) (2026-01-09)


### Added

* initial commit of reference guide ([21de7d2](https://github.com/MartinM10/dev-reference-guide/commit/21de7d220c2eb10b801b4d7fb3feeaf3dfcfdb3d))


### Changed

* translate contributing guide to spanish ([811be3e](https://github.com/MartinM10/dev-reference-guide/commit/811be3e4047c2ab8eb8ce4cf3d7d24b335b4b751))

## [Unreleased]

### Added

- Migrate template from JavaScript to Python
- Add `pyproject.toml` for Python project configuration
- Add `ruff` as linter and formatter
- Add `pre-commit` hooks for commit validation

### Changed

- Replace `npm`/`eslint` with `pip`/`ruff`
- Replace `husky` with `pre-commit`
- Update CI workflow for Python
- Configure CHANGELOG format to follow Keep a Changelog standard

### Removed

- Remove JavaScript files (`package.json`, `eslint.config.js`, etc.)
- Remove Node.js dependencies

---

## [1.1.0] - 2026-01-08

### Added

- Math utility functions (`multiply`, `divide`, `formatVersion`)

## [1.0.0] - 2026-01-08

### Added

- Initial template setup with CI/CD and conventional commits

### Fixed

- Add explicit token to release-please workflow
- Simplify release-please configuration

[Unreleased]: https://github.com/MartinM10/org-release-template/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/MartinM10/org-release-template/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/MartinM10/org-release-template/releases/tag/v1.0.0
