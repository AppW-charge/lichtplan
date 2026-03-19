# Lichtplan — Verlichtingsplanner / Zoeker

Standalone HTML tool voor het aanmaken en beheren van verlichtingsplannen op grondplantekeningen.

## Features
- PDF en PNG/JPG grondplan uploaden (hoge resolutie rendering via PDF.js)
- Armaturen en elementen plaatsen, slepen en herpositioneren
- Kabels tekenen met dynamische hoekpunten (sleepbaar)
- Kringen met kabelnummer automaat (auto-oplopende labels)
- Zoekfunctie op naam, nr, type, kabel
- Stuklijst + CSV export
- Project opslaan/laden (.vcp)
- Eigen componenttypes toevoegen

## Deploy
E�n enkel bestand: `index.html` — geen build stap nodig.

### Cloudflare Pages
1. Push naar GitHub repo `lichtplan`
2. Cloudflare Pages → New project → Connect GitHub repo
3. Build settings:
   - Framework: **None**
   - Build command: *(leeg laten)*
   - Output directory: `/` (of `.`)
4. Deploy

### Lokaal
Gewoon `index.html` openen in browser. Werkt volledig offline behalve Google Fonts + PDF.js CDN.
