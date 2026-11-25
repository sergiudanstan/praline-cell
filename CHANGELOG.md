# Changelog

All notable changes to this project are documented here. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project uses
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2026-11-25

First tagged release of the praline packing cell digital twin (a delta robot and two Epson T3 SCARA robots in a single `index.html`). Published at https://sergiudanstan.github.io/praline-cell/.

### Added
- Page smoke test (`npm run test:smoke`) and the existing logic checks (`npm test`, plus a `--perturb` run that must fail) run in CI on every push and pull request.
- CI, CodeQL, OpenSSF Scorecard and a tag-triggered release workflow with build provenance; Dependabot for actions and npm.
- `package.json` as the version source, `SECURITY.md`, `CONTRIBUTING.md` and this changelog.

[Unreleased]: https://github.com/sergiudanstan/praline-cell/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/sergiudanstan/praline-cell/releases/tag/v0.1.0
