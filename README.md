# HTML with Tailwind CSS CV

## Requirements

- [Bun](https://bun.sh/)

## Installation

```bash
# Install dependencies
bun install

# Run in development mode (with watch)
bun run build:css

# Build for production
bun run build
```

## 🌐 GitHub Pages

This project is configured to automatically deploy to GitHub Pages using GitHub Actions.

The page will be available at: [https://h1v35.github.io/jorge-higes-cv](https://h1v35.github.io/jorge-higes-cv/)

## Development

To compile Tailwind CSS and see live changes:

```bash
bun run build:css
```

Open `src/index.html` in your browser to view the CV.

## Export to PDF (A4 size)

1. Open `src/index.html` in your browser.
2. Press `Cmd+P` (Mac) or `Ctrl+P` (Windows/Linux).
3. In the print options, select "Save as PDF".
4. Set the paper size to **A4** and margins to "None" for best results.
5. Save the PDF file.

You can customize the CV design by editing the HTML and Tailwind classes in `src/index.html`.
