# [CSpell](https://cspell.org/) for Zed

This extension uses [cspell-lsp](https://github.com/vlabo/cspell-lsp) under the hood.
All configuration is fully compatible with cspell-lsp.

## Global config

cspell-lsp also reads the global cspell.json in:

- Linux: ~/.config/cspell/
- macOS: ~/Library/Preferences/cspell/
- Windows: %AppData%\cspell\Config\ -> Usually: C:\Users\<username>\AppData\Roaming\cspell\config


## Use dictionary

1. Install:
  ```bash
  npm install -g @cspell/dict-de-ch
  npm install -g cspell
  cspell link add @cspell/dict-de-ch
  ```
2. Modify `cspell.json`
  ```json
  {
    "dictionaries": ["de-ch"]
  }
  ```
3. Execute command: `editor: restart language server`
