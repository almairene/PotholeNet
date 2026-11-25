# PotholeNet Simulator

Interactive smart-road simulation demonstrating pothole detection, V2V alerts, geotagged reporting, and municipal repair dispatch.

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```powershell
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Publish with GitHub Pages

1. Push this folder to a public GitHub repository.
2. Open **Settings → Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Select `main` and `/ (root)`.
5. Share the generated GitHub Pages URL.

## Bharat RoadGuard demo

Open `bharat-roadguard.html` directly, or use the local server above. It includes:

- Coimbatore Leaflet road map with pothole and vehicle markers
- Citizen photo/report journey with offline-style demo states
- Authority ticket assignment and CSV export
- Contractor job actions and verification flow
- Analytics, SLA, recurrence, and public scorecards
