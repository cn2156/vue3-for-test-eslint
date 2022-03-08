# vue3-for-test-eslint

Test for ESLint.

OS: macOS Monterey 12.2.1(21D62)

## Steps

VS Code:

- Delete user's setting folder: .vscode
- Delete user's folder: Library/Application Support/Code
- Download:
  - https://code.visualstudio.com/updates/v1_65
  - https://code.visualstudio.com/updates/v1_64
- Unzip
- Run VS Code app
  - install extensions: ESLint, Prettier, Volar
- Change settings in VS Code
- Open project folder
- In VS Code Terminal panel run: npm install
- Open src/App.vue
- Open VS Code Probolems panel

## VS Code: 1.65

Version: 1.65.0 (Universal)
Commit: b5205cc8eb4fbaa726835538cd82372cc0222d43
Date: 2022-03-02T11:11:20.886Z
Electron: 13.5.2
Chromium: 91.0.4472.164
Node.js: 14.16.0
V8: 9.1.269.39-electron.0
OS: Darwin x64 21.3.0

ESLint v2.2.2
Prettier - Code formatter v9.3.0
Vue Language Features (Volar) v0.32.1

VS Code settings.json

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.formatOnType": true,
  "editor.fontSize": 18
}
```

Probloems panel:

```
App.vue src
	An import declaration can only be used at the top level of a module. ts(1473)[7,1]
```

Output panel:

```
[Info  - 8:17:02 AM] ESLint server is starting
[Info  - 8:17:03 AM] ESLint server running in node v14.16.0
[Info  - 8:17:03 AM] ESLint server is running.
[Info  - 8:17:04 AM] ESLint library loaded from: /....../vue3-for-test-eslint/node_modules/eslint/lib/api.js
```

## VS Code: 1.64.2

Version: 1.64.2 (Universal)
Commit: f80445acd5a3dadef24aa209168452a3d97cc326
Date: 2022-02-09T22:00:58.347Z
Electron: 13.5.2
Chromium: 91.0.4472.164
Node.js: 14.16.0
V8: 9.1.269.39-electron.0
OS: Darwin x64 21.3.0

ESLint v2.2.2
Prettier - Code formatter v9.3.0
Vue Language Features (Volar) v0.32.1

VS Code settings.json

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.formatOnType": true,
  "editor.fontSize": 18
}
```

Probloems panel:

```
No problems have been detected in the workspace.
```

Output panel:

```
[Info  - 8:30:58 AM] ESLint server is starting
[Info  - 8:31:00 AM] ESLint server running in node v14.16.0
[Info  - 8:31:00 AM] ESLint server is running.
[Info  - 8:31:03 AM] ESLint library loaded from: /....../vue3-for-test-eslint/node_modules/eslint/lib/api.js
```
