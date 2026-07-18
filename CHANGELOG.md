# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2026-07-18]
### Added
- Native global `fetch` API implementation.
- Explicitly declared `moment` dependency and added `eslint` dev dependency in `package.json`.
- Added `.eslintrc.json`, `.github/dependabot.yml`, `CODE_OF_CONDUCT.md`, and this `CHANGELOG.md`.
- Added an update guide to the `README.md`.

### Changed
- Replaced the deprecated `node-fetch` and `request` dependencies with native `fetch` to fix "Premature close" errors on Electron.
- Corrected the license type to MIT and added relevant keywords in `package.json`.
- Standardized project references to `MagicMirror²` and updated URLs to `MagicMirrorOrg/MagicMirror`.
- Renamed the license file from `LICENCE` to `LICENSE`.
