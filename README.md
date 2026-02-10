## Fresca Vibe Theme

A VS Code theme that makes your editor feel like an ice‑cold citrus soda: crisp dark can, fizzy aqua highlights, and neon‑lime pops for important things.

### Install locally

- **1. Install `vsce` (if you don’t have it)**

```bash
npm install -g @vscode/vsce
```

- **2. From this folder, package the extension**

```bash
cd /Users/fionacai/fresca
vsce package
```

This will create a `.vsix` file like `fresca-vibe-theme-0.0.1.vsix`.

- **3. Install the `.vsix` into VS Code**
  - Open the command palette and run `Extensions: Install from VSIX...`
  - Choose the generated `.vsix` file.

- **4. Activate the theme**
  - Open the command palette and run `Preferences: Color Theme`
  - Pick **“Fresca Vibe”**.

### Tuning the vibe

- **Too dark / too bright?** Adjust `editor.background` or `editor.foreground` in `themes/fresca-vibe-color-theme.json`.
- **Want different “fizz” colors?** Tweak accent colors like `F6FF9C` (neon‑lime), `6EE7F5` (bubbly cyan), and `4FA2A8` (sea‑foam aqua).

