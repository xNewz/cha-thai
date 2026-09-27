# Contributing to Cha Thai

First off, thank you for considering contributing to the **Cha Thai** theme! It's people like you that make the open-source community such a fantastic place to learn, inspire, and create.

## 🛠️ Getting Started

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (LTS recommended)
- [npm](https://www.npmjs.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

### Running the Extension Locally
1. Clone or open this repository in VS Code.
2. Press `F5` (or navigate to **Run and Debug** → "Extension").
3. This will open a new **Extension Development Host** window with the theme loaded.

## 🎨 Development Guidelines

- **Theme Files:**
  - Light theme: `themes/cha-thai-color-theme.json`
  - Dark theme: `themes/cha-thai-dark-color-theme.json`
- **Testing Your Changes:**
  - Use the Command Palette (`Ctrl+Shift+P` / `⇧⌘P`) → `Preferences: Color Theme` → select **Cha Thai** or **Cha Thai Dark**.
  - Test across multiple languages you use most (e.g., JavaScript/TypeScript, Python, HTML/CSS, JSON, Markdown).
  - Inspect UI elements carefully (status bar, tabs, side bar, lists, notifications).

## 📦 Packaging and Publishing

*Note: Publishing is restricted to maintainers.*

- **Package locally:** `npm run package` (uses `vsce` to create a `.vsix` file).
- **Publish to VS Marketplace:** `npm run publish:vsce`
- **Publish to Open VSX:** `npm run publish:ovsx`

## 📝 Pull Request Process

1. Create a feature branch from the `main` branch (e.g., `feature/new-syntax-color`).
2. Keep your changes focused and minimal to ease the review process.
3. If your changes alter the visual appearance, please include **Before/After screenshots** in your PR.
4. Update `README.md` and `CHANGELOG.md` if your changes introduce new features or behavior.
5. Ensure your JSON changes are valid and properly formatted.

## 🐛 Reporting Issues

If you find a bug or have a suggestion, please [open an issue](https://github.com/xNewz/cha-thai/issues).
- Use a clear and descriptive title.
- Provide steps to reproduce the issue.
- Include your VS Code version, Operating System, and relevant code snippets or screenshots.

Thank you for helping make Cha Thai better! 🧋
