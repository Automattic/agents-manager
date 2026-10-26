# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.0-alpha] - unreleased

This is an alpha version! The changes listed here are not final.

### Added
- Connection: Show connection errors on the Connectors card, and keep showing the connection owner when their account connection breaks.
- Connection: Transfer connection ownership to another connected administrator from the Connectors page.

### Changed
- Connection: Show a clear message when connecting the site to WordPress.com from the Connectors card fails, instead of WordPress.com's raw error text.

### Fixed
- Connection: Translate the Connectors card's text on sites that don't use English.

## [0.2.0] - 2026-09-23
### Changed
- Make the help and Ask AI admin bar nodes available from the admin-bar REST endpoints, with the label, icon and destination a client needs. [#51657]
- Name the admin bar's AI chat button “Agent”, render an “Agent” label beside its icon while the chat is hidden, and rename its `meta.icon` key from `ask-ai` to `sparkle`. [#51926]
- Update dependencies. [#50044]

### Fixed
- Status: Detect a site served on any 127.0.0.0/8 loopback address, or on 0.0.0.0, as a local site. [#51311]

## [0.1.2] - 2026-06-25
### Changed
- Update dependencies. [#49612]

## 0.1.0 - 2026-06-10
### Added
- Initial version: standalone plugin that loads the Jetpack Agents Manager package.

[0.3.0-alpha]: https://github.com/Automattic/agents-manager/compare/v0.2.0...v0.3.0-alpha
[0.2.0]: https://github.com/Automattic/agents-manager/compare/v0.1.2...v0.2.0
[0.1.2]: https://github.com/Automattic/agents-manager/compare/v0.1.0...v0.1.2
