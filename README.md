# CodeSpace — Basic

A simple static GitHub Pages app: drag/drop or choose files, then press Run.

## Publish
Upload `index.html` to the root of your GitHub repository and enable GitHub Pages from Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

## Supported behavior
- HTML/CSS/JavaScript files are combined into a sandboxed browser preview.
- Other languages are sent to the public Piston execution API using the first recognized file.
- File extensions are used to identify languages automatically.

## Limitations
- This is a basic browser-only demo. It does not provide secure isolation for untrusted HTML/JavaScript beyond a sandboxed iframe.
- The public execution API requires internet and may impose availability or rate limits.
- Multi-file builds, package installation, project dependencies, and persistent storage are not supported.
- Do not upload secrets or run code you do not trust.