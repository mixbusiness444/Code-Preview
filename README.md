# CodeSpace

A lightweight browser IDE that can be hosted on GitHub Pages.

## Publish it on GitHub

1. Create a GitHub repository named `codespace`.
2. Upload `index.html` to the repository's root folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait a minute and open the Pages URL shown there.

## Features

- Code editor with syntax highlighting (CodeMirror)
- HTML preview in a sandboxed iframe
- Run supported languages through the Piston API
- Upload multiple files, switch between them, and download as ZIP
- Standard input for programs

## Important limitations

- This is a browser-only starter version. It does not include user accounts, cloud project storage, or a private execution server.
- Non-HTML code is sent to the third-party Piston execution API. Its availability, language versions, rate limits, and browser access may change.
- The starter runner sends the active file only. It does not compile multi-file projects or install project dependencies.
- Never run untrusted code or submit secrets, passwords, or API keys.
- External CDN libraries and the execution API require an internet connection.

## Technology

Plain HTML/CSS/JavaScript, CodeMirror 5, JSZip, and the Piston API.