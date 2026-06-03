# Sew-Out Approver

Sew-Out Sheet Generator + Approver for Rhoback embroidery production.

**Live tool:** https://nt-rhoback.github.io/sew-out-approver/

## What it does

Two side-by-side panels in one self-contained HTML file:

**Generator** — Build a fillable Sew-Out Approval PDF:
- Drag a `.dst` file to auto-fill customer, logo name, height/width
- Add thread count + colors, sew-out photo, up to 9 reference images
- Each reference photo supports rotate (90°) and crop (drag-select)
- Outputs `SOA_[LogoName]_[width]in_[ver].pdf`

**Approver** — Stamp APPROVED or REVISION NEEDED on an existing sheet:
- Drop the sew-out PDF → reads existing field values
- Pick approval status, edit notes (replace or append)
- Customer signature: Via + By + Date (defaults to today, override possible)
- Outputs `[name] - APPROVED.pdf` or `[name] - REJECTED.pdf`

## License / use

Internal Rhoback tool. Self-contained — no server, no backend. Open in any modern browser.
