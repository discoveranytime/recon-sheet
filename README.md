# Reconstitution Sheet — Interactive Reference

An interactive, dark-mode HTML reproduction of the **“RECONSTITUTION CHART — BASED ON DOSE”** PDF.

## What's inside

- **17 vial sizes** (2 mg – 60 mg), **132 vial/BAC-water combinations**, **3,597 drawing-unit values**
- Every value **and** its red/orange/yellow/green rating reproduced cell-for-cell from the source chart
- 5 chapters: Quick reference · Vial reference · Draw finder · The math · Important notes

## How to use

1. Open `index.html` in any modern browser (no internet needed — fully self-contained).
2. **Vial reference**: pick a vial size, read any dose as syringe drawing units. Click a value to copy it.
3. **Draw finder**: pick your vial + dose to see every BAC-water option ranked from ideal to avoid.
4. **The math**: three-step worked example + a mini calculator showing how each number is derived.

## Interactions

- Sticky chapter navigation with scroll-spy
- Vial-size pills, dose-column highlighter, click-to-copy with toast confirmation
- Tier-ranked BAC recommendations, live formula calculator

## Notes on accuracy

- All 3,597 values were extracted geometrically from the source PDF and verified cell-by-cell.
- **115 cells** (mostly in the 20–50 mg vial tables) print an exact `X.5` result as the next whole unit (e.g. a calculated 6.5 appears as 7.0), differing from the chart's own "nearest 0.5" rule. These are reproduced exactly as printed and flagged in Chapter 4.
- BAC water is assumed at 100 units per mL, per the source chart.

## Disclaimer

Educational reference only — not medical advice. Always verify calculations independently and consult a qualified professional.
