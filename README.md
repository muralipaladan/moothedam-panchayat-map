# Moothedam Grama Panchayat Interactive Map

**Prepared for Aiswary V · Moothedam Panchayat Office**

## Live Map (after enabling Pages + uploading data)
https://muralipaladan.github.io/moothedam-panchayat-map/

## Color scheme (smart complementary design)
- **Wards**: Party-coloured fills (semi-transparent)
  - INC → Blue `#1a73e8`
  - IUML → Green `#2e7d32`
  - CPI(M) → Red `#c62828`
  - Independent → Purple `#6a1b9a`
  - White border for clear separation
- **Moothedam Panchayat boundary**: Strong dark blue outline `#0d47a1` (weight 4)
- **Neighbouring panchayats** (Chungathara, Edakkara, Karulai, Vazhikkadavu): Warm orange dashed outline `#e65100` + light cream fill – complementary to the cool party colours so boundaries stand out clearly without clashing.

## How to make it fully work
1. **Enable GitHub Pages**
   - Repo → Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / Folder: `/ (root)`
   - Save

2. **Upload the two GeoJSON files** (required for wards & neighbours to appear)
   - Go to the repo main page
   - Click **Add file → Upload files**
   - Upload:
     - `moothedam_wards.geojson`
     - `neighbors.geojson`
   - Commit directly to `main`

   (These files are ready in the conversation artifacts / previous generation. If you need me to re-provide the exact files, say so.)

3. Wait 1–2 minutes after Pages is enabled + files uploaded.

## Features already in the map
- Google Hybrid / Google Road / OSM / Esri Satellite base layers
- Click any ward → member name (Malayalam + English), party, age, gender, house, symbol, ward code, population
- Live GPS blue dot (mobile)
- Navigate to ward via Google Maps
- Add / edit / delete / export / import pins & notes (localStorage)
- Responsive mobile-friendly UI

Made with Leaflet for Aiswary V.