# Tandem

Tandem is a contextual AI companion for Obsidian. It helps you discuss, improve and organize Markdown notes without applying changes automatically.

## Features

- Contextual chat from the right sidebar
- `/tandem` actions and custom actions
- Reviewable note edits and vault organization plans
- Background suggestions after a pause in editing
- Per-change previews, confidence and priority
- Apply, ignore or postpone suggestions
- English by default, French when Obsidian is French
- Configurable local AI CLI

## Installation

Copy this repository into `.obsidian/plugins/codex-sidebar`, then enable **Tandem** in Obsidian's community plugins settings. The technical plugin id remains unchanged to preserve existing installations.

The default CLI command is `codex` on macOS/Linux and `codex.cmd` on Windows. It can be changed in Tandem's settings.

## Development

The plugin is intentionally dependency-free. Validate changes with:

```bash
node --check main.js
```

The version is changed only when a release is published.
