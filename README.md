# Moothedam Grama Panchayat Interactive Map

**Prepared for Aiswary V · Moothedam Panchayat Office**

## What is included

- **18 Ward polygons** (2024 Delimitation – official Kerala data)
- **Neighbouring panchayats** outline (Chungathara, Edakkara, Karulai, Vazhikkadavu)
- Base layers: Google Hybrid / Road, OpenStreetMap, Esri Satellite
- Live GPS location
- Navigate to ward via Google Maps
- Pins & notes (add / edit / delete / export / import) – stored in browser
- Mobile-friendly UI

## Wards (18)

| No | Ward Name        |
|----|------------------|
| 1  | Marathinkadav    |
| 2  | Nellikkuth       |
| 3  | Thalippadam      |
| 4  | Kalkulam         |
| 5  | Balamkulam       |
| 6  | Karappuram       |
| 7  | Payimpadam       |
| 8  | Cholamunda       |
| 9  | Vellaramunda     |
| 10 | Palankara        |
| 11 | Vattappadam      |
| 12 | Kuttikkad        |
| 13 | Nellipoil        |
| 14 | Moothedam        |
| 15 | Chamaparambu     |
| 16 | Muppini          |
| 17 | Maramvettichal   |
| 18 | Chemmanthitta    |

## Color scheme

- Each ward has a distinct coloured boundary (cycling palette)
- Neighbouring panchayats → orange dashed outline

## Member details (optional)

Ward polygons are ready. To show elected member info in the popup, add these properties to each feature in `wards_final.geojson`:

- `party` / `party_full` (INC, IUML, CPI(M), Independent…)
- `member_ml`, `member_en`
- `age`, `gender`, `house`, `symbol`
- `ward_code`, `total_pop`, `males`, `females`

The map will automatically display them when present.

## Deploy on GitHub Pages

1. Upload the 3 files to repo root:
   - `index.html`
   - `wards_final.geojson`
   - `neighbors_final.geojson`
2. Settings → Pages → Deploy from branch `main` / root
3. Wait 1–2 minutes

## Data source

Ward boundaries: Kerala Delimitation Commission 2024  
(via https://wardmap.ksmart.live / Vonter/kerala-wards)

Made with Leaflet.
