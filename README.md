<div align="center">
<img src="https://raw.githubusercontent.com/adanperez/nada-theme/master/assets/nada-icon-v2.png"  width="364"/>
</div>

# Nada Theme
A dark theme full of nada. 

Made for Typescript, Javascript, React, Svelte, CSS, SASS, Python, and many others.

![](assets/example2.png)
![](assets/example1.png)

Elements of this theme are inspired by *Dracula* and *Field Lights* themes. 

## Developing

The project already includes a launch config (`.vscode/launch.json`), so you can preview changes live in VS Code.

1. **Open the folder in VS Code.**

   ```sh
   code /path/to/nada-theme
   ```

2. **Launch the Extension Development Host.** Press **F5** and choose the **Extension** config if prompted. A second window titled `[Extension Development Host]` opens with your local theme loaded as an extension.

3. **Select the theme in the new window.** Press `Cmd+K Cmd+T` and pick **Nada**. If the marketplace version is also installed, you may see two "Nada" entries. Disable the marketplace version in the dev host window, or temporarily bump the local `version` in `package.json`.

4. **Edit the theme file.** In your original window, open `themes/nada-color-theme.json` and change colors:
   - `colors` is the UI: editor background, sidebar, status bar, etc.
   - `tokenColors` is syntax highlighting.

5. **Save and check the dev host window.** VS Code watches the theme file, so changes show up within a second or so. If a change doesn't appear, run **Developer: Reload Window** in the dev host (`Cmd+R`).

6. **Find the right scope or key to change.** In the dev host, open a code file and run **Developer: Inspect Editor Tokens and Scopes** (`Cmd+Shift+P`). Click a token to see its TextMate scope and the theme rule styling it, then use that scope in `tokenColors`.

7. **Test with different languages.** Open sample CSS, JS, React, and Svelte files in the dev host.

8. **Stop debugging when done.** Close the dev host window or press the stop button.

### Quick experiments

To try a color without touching the theme file, add it to your user `settings.json`. These apply instantly:

```json
"workbench.colorCustomizations": {
  "editor.background": "#1e1e1e"
},
"editor.tokenColorCustomizations": {
  "textMateRules": [
    { "scope": "comment", "settings": { "foreground": "#888" } }
  ]
}
```

Once you like the result, copy the values into the theme JSON.

### Publishing

1. Bump `version` in `package.json`.
2. Run `vsce publish` (requires `@vscode/vsce` and your publisher token).


&copy; Adan Perez 2026
