# PulseSpeed — Internet Speed Test

A responsive, single-page internet speed test website built with HTML, CSS, and JavaScript.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser while connected to the internet.
3. Click **Start speed test**.

## Features
- Download speed, upload speed, ping/latency, and jitter
- Animated gauge and live metric bars
- Browser-reported connection type and estimated downlink (when supported)
- Connection quality summary
- Recent test history stored locally in the browser
- Responsive dark UI and FAQ section

## Important notes
- The page uses Cloudflare's public speed test endpoints. Browser/network policies, ad blockers, or CORS changes may prevent a measurement from completing.
- Upload may be blocked on some networks; the UI shows `N/A` if that happens.
- Browser-based measurements are estimates and can differ from ISP/router tests.
- For a production service with consistent accuracy and your own server selection, deploy a backend or integrate a reputable speed-test SDK/API. Do not describe browser-reported connection estimates as guaranteed results.
