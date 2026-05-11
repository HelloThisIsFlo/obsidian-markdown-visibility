# Changelog

All notable changes to the Markdown Visibility plugin will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.5] - 2026-05-11

### Added
- **Hide highlight markers**: Toggle visibility of `==` highlight syntax using the multi-layer CSS approach (`font-size: 0`, `visibility: hidden`, etc.) targeting `cm-formatting-highlight`
- **Hide task markers**: Toggle visibility of `[ ]`/`[x]` task checkbox brackets using `color: transparent` with negative `letter-spacing` to preserve native checkbox widget rendering and minimise text shift on active lines
- Both new marker types include granular toggle controls in the settings panel, consistent with existing marker types

## [1.0.4]

### Added
- Interactive toggle command (configurable keyboard shortcut via Hotkeys settings)
- Settings panel with global enable/disable toggle and granular per-marker controls
- Status bar item showing current state (click to toggle)
- Persistent settings saved and restored across Obsidian sessions
- Dynamic CSS injection based on plugin state and user preferences
- Support for hiding: headers, bold, italic, links, code, blockquotes, lists

## [1.0.0] - 2025-10-26

### Added
- Initial release of Markdown Visibility plugin
- CSS-based hiding of Markdown formatting markers in Live Preview

[1.0.5]: https://github.com/miztizm/obsidian-markdown-visibility/compare/1.0.4...1.0.5
[1.0.0]: https://github.com/miztizm/obsidian-markdown-visibility/releases/tag/1.0.0

