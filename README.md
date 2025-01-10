# [CSpell](https://cspell.org/) for Zed

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
