# gm for Kilo CLI

## Installation

### Global (recommended)

**Windows and Unix:**
```bash
git clone https://github.com/AnEntrypoint/glootie-kilo ~/.config/kilo/plugin && cd ~/.config/kilo/plugin && bun install
```

**Windows PowerShell:**
```powershell
git clone https://github.com/AnEntrypoint/glootie-kilo "\$env:APPDATA\kilo\plugin" && cd "\$env:APPDATA\kilo\plugin" && bun install
```

### Project-level

**Windows and Unix:**
```bash
git clone https://github.com/AnEntrypoint/glootie-kilo .kilo/plugins && cd .kilo/plugins && bun install
```

## Features

- MCP tools for code execution and search
- State machine agent policy (gm)
- Git enforcement on session idle
- AST analysis via thorns at session start

The plugin activates automatically on session start.
