# Xed-Editor Theme Template

This is a theme template for [Xed-Editor](https://github.com/Xed-Editor/Xed-Editor), allowing you to create custom light and dark color schemes for the application, editor and terminal.
You can use this template as a starting point to build your own themes.

> [!TIP]
> See the [documentation](https://xed-editor.github.io/Xed-Docs/docs/themes/#creating-custom-themes) page for details on customizing the theme.

## Getting started

1. Clone this repository
2. Edit `theme.json` to customize your theme's colors
3. Update `manifest.json` with your package metadata (at least `id`, `name`, `version`, `author`, `repository`)
4. Run `node build.js` to produce the `.xed` package in `output/`

## Build

```bash
node build.js
```

This creates `output/<id>.xed`, a ZIP package containing `theme.json`, `manifest.json` and when present `README.md`, `icon.png` and `CHANGELOG.md`.

## Install locally

Go to **Xed-Editor → Settings → Store → Install from storage** and select the built `.xed` file.

## Publish to the store

Upload the built `.xed` on [xed-editor.app](https://xed-editor.app). You can find more information in the documentation.
