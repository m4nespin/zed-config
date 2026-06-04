# Zed Config

My personal Zed config files.

## Contents

- `settings.json` - portable Zed preferences.
- `AGENTS.md` - agent instructions used by Zed.
- `themes/` - custom themes, when present.

## Usage

Clone or copy these files into your Zed config directory.

On Windows, that directory is typically:

```powershell
$env:APPDATA\Zed
```

## Privacy

This repo intentionally excludes Zed runtime state from `%LOCALAPPDATA%\Zed`,
including logs, databases, extension caches, threads, prompts, and crash files.
Before committing new files, check for tokens, credentials, account identifiers,
private paths, and other machine-specific data.
