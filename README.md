# Voiton Theme for VS Code

A VS Code port of **Voiton**, originally designed by Mahin for Zed.

## Variants

- **Voiton Dark** — neutral graphite / blue-violet primary
- **Voiton Rose** — restrained rose / violet
- **Voiton Cyan** — cool cyan / blue
- **Voiton Violet** — violet / cyan

The port maps the original Zed palette into VS Code workbench colors, TextMate token scopes, and semantic token colors. The source Zed theme contains four variants and a detailed syntax palette; those roles are preserved as closely as VS Code's theming model allows.

## Install locally

1. Extract this folder.
2. Open it in VS Code.
3. Press `F5` to launch an Extension Development Host, or package it as a VSIX.
4. Open **Preferences: Color Theme** and select a Voiton variant.

For a local VSIX, install `@vscode/vsce` and run:

```bash
npx @vscode/vsce package --no-dependencies
```

Then install the generated `.vsix` from **Extensions → ... → Install from VSIX**.

## Design intent

Voiton keeps the editor surface restrained, uses low-contrast structural chrome, and reserves saturated colors for semantic syntax, focus, diagnostics, Git state, and interactive states.

The theme is intentionally declarative: no runtime extension code is required.

## Source

Original Zed theme: `Voiton` by Mahin.
# visqode-theme
