# pdf-mobile-sdk test fixtures

Public test documents for the pdf-mobile-sdk PR test pipeline (Linear LP-528).

- Files are published as assets of immutable releases (`corpus-v1`, ...). A file whose bytes change is published again under a new release; existing release assets are never replaced.
- `manifest.json` in each release lists every file with its size, SHA-256 and download URL.
- `<id>.json` documents describe a remote document load: `{ "id": ..., "url": ... }`.
