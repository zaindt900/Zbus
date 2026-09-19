# ZBus 🚌📍

A beginner-friendly Istanbul bus web app MVP.

## What works now
- Real browser GPS with high accuracy.
- Interactive OpenStreetMap map.
- Real nearby bus-stop discovery through OpenStreetMap/Overpass.
- Stop markers and distance list.
- Basic search using Nominatim.
- Light/dark mode.
- Your ZBus logo.
- Responsive mobile/tablet/desktop layout.

## Important
This version does **not** invent live bus positions. IETT publishes route/stop information and operates the official Otobüsüm Nerede service, but a public unauthenticated live-vehicle API endpoint was not identified during implementation. The project therefore keeps the live-bus layer separate until an official/public endpoint is confirmed.

## Run
Open `index.html` from a local web server (recommended because browser geolocation usually requires HTTPS or localhost).
For example:
- VS Code + Live Server
- `python -m http.server 8000`

Then open `http://localhost:8000`.
