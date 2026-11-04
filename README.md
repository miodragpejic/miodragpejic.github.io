# miodragpejic.github.io
# Card Centering Report

Measure trading card centering from flatbed scans (Gauge) or phone photos (Camera) and check it against PSA, BGS or a custom grading scale.

**Live:** https://miodragpejic.github.io/

## Features
- **Gauge**: 8 draggable guides on card edges and print borders, zoom to pixel level, rotate the scan (90° turns and fine angle).
- **Camera**: finds the card in a photo, removes perspective, auto-places the print-border guides.
- **Grading**: PSA, BGS (locked defaults, unlockable) and Custom scales, front and back. The larger side is rounded up to the next whole percent (stricter reading).
- **Export**: one .zip with PDF report, JSON measurement and PNG image (2 mm margin), or each part separately.
- **Import**: open a .zip (or .json + .png) to review a measurement, with checks for edited images or numbers.

## Privacy
Everything runs in the browser. Images are never uploaded.

## Files
- `index.html`: the whole app.
- `.nojekyll`: tells GitHub Pages to serve files as they are.

Uses jsPDF 2.5.1 (cdnjs) for the PDF report and Google Fonts for typography.

Not affiliated with or endorsed by PSA, Beckett or any grading company.
