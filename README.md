# Frank Valdez Resume

This repo publishes Frank Valdez's current resume through GitHub Pages. The site now displays the PDF version directly and keeps the LaTeX source beside it for edits.

## Files

- `index.html`: landing page with embedded PDF preview and file links
- `FrankValdezResumeJune_IconSpaced.pdf`: current one-page resume
- `FrankValdezResumeJune_IconSpaced.tex`: LaTeX source for current resume
- `FrankValdezResumeJune_IconSpaced_preview.png`: browser-friendly preview image generated from the PDF

## Local Preview

Run a static server from repo root:

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Updating

Replace both resume files when publishing a new version. Regenerate the preview image from the new PDF, keep matching base names for the PDF and TeX source, then update links in `index.html` if file names change.
