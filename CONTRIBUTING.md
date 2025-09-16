# Contributing to Cha Thai

Thanks for your interest in improving the Cha Thai theme! Contributions are welcome and appreciated.

## Getting Started

- Requirements: Node.js LTS, npm, VS Code
- Install dependencies (optional, for publishing helpers):
  - `npm install` (only if `devDependencies` are added later)
- Run the extension in a Dev Host:
  - Open this repo in VS Code
  - Press F5 or use Run and Debug → "Extension"

## Development Tips

- Theme file: `themes/cha-thai-color-theme.json`
- Icon/screenshot: `cha-thai-icon.jpg`
- Test across languages you use most (JavaScript/TypeScript, Python, HTML/CSS, JSON, Markdown, etc.)

## Testing Locally

- Use the Command Palette → "Preferences: Color Theme" → select "Cha Thai"
- Inspect UI elements: status bar, tabs, side bar, lists, notifications
- Inspect syntax tokens: comments, strings, numbers, keywords, functions, classes, types

## Packaging / Publishing

- Package a `.vsix` locally:
  - `npm run package` (uses `vsce` via `npx`)
- Publish to Visual Studio Marketplace:
  - `npm run publish:vsce` (requires a VSCE token)
- Publish to Open VSX:
  - `npm run publish:ovsx` (requires an OVSX token)

Tokens are stored locally via the CLI; do not commit them.

## Pull Request Guidelines

- Create a feature branch from `main`
- Keep changes focused and minimal
- Update `README.md` or `CHANGELOG.md` if behavior or visuals change
- Ensure JSON is valid and consistent
- Add screenshots if visual changes are significant

## Reporting Issues

- Use GitHub Issues with a clear title and steps to reproduce
- Include VS Code version, OS, and (if relevant) language/file samples

Thank you for helping make Cha Thai better! 🧋
