# Change Log

## 2.1.0
- Nada: reorganized `themes/nada-color-theme.json` to match Nada Night. Workbench colors are grouped by UI area and sorted A-Z, syntax rules are grouped by language, and the file has comments and links to the VS Code docs. Colors are unchanged except where noted below.
- Nada: merged duplicate rules so each scope appears once with the color that was already winning, and removed selectors that never match in VS Code (`*url*` wildcards, `-` exclusions such as the JSON key levels, and Sublime-only scopes like `git_gutter`).
- Nada: added Markdown preview colors (quote border, code block and preformatted backgrounds, horizontal rules), an input toggle hover color, diff line and gutter backgrounds, and a teal color for CSS custom properties.
- Nada: picked up Night's newer scopes: JSDoc descriptions and tags, Tailwind `@theme` braces, CSS list commas, Markdown link brackets, and more TypeScript type-declaration punctuation.
- Nada: `editorIndentGuide.background` is now `editorIndentGuide.background1`, since the old key is deprecated (VS Code 1.71+).
- Nada Night: default text is now a warmer `#e4e0dd` (was `#d3d3d3`).
- Nada Night: TypeScript types moved from amber to a red/rose family, matching Nada.

## 2.0.0
- Added **Nada Night**, a second theme. The extension now offers both Nada and Nada Night.
- Nada Night: darker `#0b0f19` / `#0e1320` surfaces, cyan `#9ccfd8` accent, softer `#d3d3d3` text, amber TypeScript types.
- Nada Night: added Markdown preview colors (quotes, code blocks, rules), JSDoc descriptions, Tailwind `@theme` braces, and diff line backgrounds.

## 1.16.0
- Updated logo and README. Removed unused styles.

## 1.15.0
- Fixed Svelte start tag.

## 1.13.0
- Fixed missing CSS function/keyframe begin and end colors.

## 1.11.0
- Added Svelte colors.  Fixed css issues. Modified text color in elements.

## 1.10.0
- Toned down diffEditor colors.

## 1.9.0
- Modified HTML text.

## 1.8.0
- Fixed dynamic imports and modified HTML text.

## 1.7.0
- Updated logo.

## 1.6.0
- Fixed function types for TS.

## 1.5.0
- Added Decorator support for TS.

## 1.4.0
- Updated panel title color and tweaked git file colors.

## 1.3.0
- Fixed switch case statements.

## 1.2.0
- Muted tsx/jsx html colors and fixed attribute quote strings.  Tweaked some python colors.

## 1.1.0
- Updating markdown, terminal, strings, and json.
