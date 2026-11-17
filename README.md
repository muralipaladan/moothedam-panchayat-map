# Moothedam Grama Panchayat Interactive Map

**Prepared for Aiswary V · Moothedam Panchayat Office**

## Live Map
After enabling GitHub Pages (Settings → Pages → Source: Deploy from a branch → main → /root), the map will be available at:

**https://muralipaladan.github.io/moothedam-panchayat-map/**

## Features
- Google Hybrid / Google Road / OSM / Esri Satellite base maps
- 18 Moothedam wards coloured by party (INC / IUML / CPI(M) / Independent)
- Click/tap ward → Member name (ML + EN), party, age, gender, house, symbol, ward code, population
- Neighbouring panchayat boundaries (Chungathara, Edakkara, Karulai, Vazhikkadavu)
- Live GPS blue dot on mobile
- Navigate button → Google Maps directions
- Add Pin + Notes (localStorage, export/import JSON, edit/delete)

## How to enable Pages
1. Go to the repository Settings → Pages
2. Under "Build and deployment" → Source: Deploy from a branch
3. Branch: `main` / folder: `/ (root)`
4. Save. Wait 1-2 minutes.
5. Open https://muralipaladan.github.io/moothedam-panchayat-map/

The map HTML is already in the repo. The GeoJSON data files need to be uploaded (or the map can be made self-contained). Contact for full data push if needed.

Made with Leaflet.