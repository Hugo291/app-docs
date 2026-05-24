# App Docs

Privacy policies and legal documents for my Android apps. Served via GitHub Pages.

## Apps

### Routine Five
- [Privacy Policy FR](https://hugo291.github.io/app-docs/routine-five/privacy.html)
- [Privacy Policy EN](https://hugo291.github.io/app-docs/routine-five/privacy.en.html)

### MiniGeste
- [Privacy Policy EN](https://hugo291.github.io/app-docs/minigeste/privacy.html)

## Structure

```
app-docs/
├── index.html
├── README.md
├── minigeste/
│   ├── index.html         (redirect → privacy.html)
│   └── privacy.html       (EN)
└── routine-five/
    ├── privacy.html       (FR)
    └── privacy.en.html    (EN)
```

To add a new app: create a folder `<app-slug>/`, add `privacy.html` (and any other legal docs), update the index.
