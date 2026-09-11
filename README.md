# dimmer-ext

Chrome extension that tracks reading time per tab

## Examples

```bash
# click the toolbar icon to see today's reading time
```

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## What it does

- Popup shows today's total focus time
- Per-tab time persisted to chrome.storage
- No remote calls, everything stays local
- Manifest V3, service worker based

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── roadmap.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## License

MIT - see [LICENSE](LICENSE).
