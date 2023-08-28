# Deno format vendored files bug

Formatting a vendored file throws an error in vscode.

## Steps to reproduce

1. Clone this repository
2. Open `vendor/esm.sh/v124/@twind/core@1.1.3/deno/core.mjs`
3. Open command palette (CMD+Shift+P on macOS or CTRL+Shift+P on other OS'es) and select `Format document with...` -> `Deno`
