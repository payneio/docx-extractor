# docx-extractor

Extract content and metadata from Word `.docx` files.

Reads a `.docx` file and writes a JSON object containing the document's text
content and metadata (filename, size, title, author, creation date, etc.) to
stdout.

## Usage

```bash
docx-extractor document.docx       # Extract from a file
cat document.docx | docx-extractor # Read from stdin
```

## Install

```bash
uv tool install --editable .
```

## License

Copyright (C) 2026 Paul Payne. Licensed under the GNU AGPLv3 — see [LICENSE](LICENSE).
