# PROJECT KNOWLEDGE BASE

**Generated:** 2026-03-31T13:35:00Z
**Project:** EcoMóveis One-Page Website

## OVERVIEW

Static one-page website for fictional furniture company "EcoMóveis Ltda" - sustainable furniture made from FSC-certified recycled wood. Single HTML file with embedded CSS/JS, no build system required.

## STRUCTURE

```
./
├── index.html              # Main deliverable (1834 lines, 61.7KB)
├── .sisyphus/
│   ├── boulder.json       # Task session tracking
│   └── plans/
│       └── ecomoveis-site.md  # Project plan (4 tasks complete)
└── .opencode/              # IDE tooling (not project source)
```

## WHERE TO LOOK

| Task | Location | Notes |
|------|----------|-------|
| Edit website | `index.html` | All HTML, CSS, JS embedded |
| View plan | `.sisyphus/plans/ecomoveis-site.md` | Completed tasks marked |
| Task status | `.sisyphus/boulder.json` | Session tracking |

## CONVENTIONS

- **Single-file architecture**: All code in `index.html`
- **Embedded styles**: `<style>` block in `<head>`
- **Embedded scripts**: `<script>` block before `</body>`
- **No dependencies**: Pure vanilla HTML/CSS/JS
- **CDN resources**: Google Fonts + Lucide Icons only

## ANTI-PATTERNS (THIS PROJECT)

- NO external images (inline SVGs only)
- NO CSS frameworks (pure CSS)
- NO JS libraries (vanilla JS only)
- NO build system required

## UNIQUE STYLES

- **Color palette**: Green (#1B4332, #2D6A4F) + Wood tones (#C8A96E, #7B5635)
- **Typography**: Playfair Display (headings) + Inter (body)
- **Responsive**: Mobile-first, breakpoints at 768px, 1024px

## COMMANDS

```bash
# View website - open directly in browser
start index.html
# or
firefox index.html
```

## NOTES

- Website complete - all 4 plan tasks finished
- No additional development needed
- Pure static HTML - no server required
