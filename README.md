# ZBus
Istanbul bus stops & lines. Plain HTML/CSS/JS, no build step.

## Run
1. `node tools/build-data.js`  (once; needs internet; fetches official İBB/İETT stop + line lists into `data/`)
2. `npx serve .`  or  `python3 -m http.server 8000`, then open http://localhost:8000
   (GPS and the service worker need `localhost` or HTTPS.)

## Status
Working: GPS, map, nearby stops, search, favorites, TR/EN/AR (RTL), light/dark, PWA + offline page.
Not yet: live buses/arrival times (js/api.js `Live`, disabled, never simulated) and lines-per-stop (needs the official route-stop data).
For iOS home-screen icons, add PNG icons (180x180, 192, 512) to assets/icons and reference them in manifest.json.
