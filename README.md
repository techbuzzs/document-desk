# Document Desk

Turn PDFs into editable Markdown, extract text, merge documents and reorder pages.

A working utility that processes data locally in the browser. No accounts, API keys, or server file storage.

## Run

Node.js 22 or newer.

```sh
npm install
npm run build
npm run dev
```

## Features

- Text PDF to editable Markdown and plain text
- Merge PDFs, reorder or remove pages and download the result
- Generated sample PDF; all document processing stays local

## Embed

Use `?embed=1&theme=light` (or `dark`) for the compact homepage demo. Theme follows the operating system by default, with an optional saved preference.

## Deployment

Vercel serves the generated `dist` directory.

## Credits

Built by [Tech Buzzs](https://github.com/techbuzzs). Uses pdfjs-dist, pdf-lib, under their respective open source licenses.
