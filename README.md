# consult-brief

> Clinical briefings for medical consultations

## Current briefs

### `co-exposure-brief.html`

Patient briefing prepared for the RX-O2 Hyperbaric Clinic consultation. Covers the carbon monoxide and lead exposure event of 06.20.2026, symptom timeline through Day 7, treatment trial with the Vitaeris 320 chamber, current symptom status, activity tolerance, lifestyle factors, asks, and specific questions for the doctor.

**Live URL:** `https://elijahcarimbocas.github.io/consult-brief/co-exposure-brief.html`

**OG preview:** `co-exposure-brief-og.png` (1200×630)

## Deployment

GitHub Pages, deploy from `main` branch root.

1. **Settings → Pages**
2. Source: **Deploy from branch**
3. Branch: **main** · Folder: **/ (root)**

## File structure

```
consult-brief/
├── README.md
├── co-exposure-brief.html
└── co-exposure-brief-og.png
```

Single-file HTML with embedded CSS. Google Fonts (Source Serif 4, Inter, JetBrains Mono) load from CDN at view time. Print-friendly via embedded media query.

## Design

Clinical editorial aesthetic. Different from the romantic palette used in `leslie-dispatch`. Optimized for medical professionals to scan quickly.

- Background `#F8F5EF` (warm paper)
- Primary `#1A1F26` (deep slate)
- Teal accent `#2E5C66` (clinical)
- Warm accent `#B07A45` (gold, for callouts)
- Severity indicators: rose `#C77B6A`, gold `#B89968`, sage `#6F9F7D`

Typography: Source Serif 4 (display), Inter (body), JetBrains Mono (data labels and codes).

## Version history

- **v1.0** · 06.27.2026 · *co-exposure-brief* · Initial briefing for RX-O2 consultation
