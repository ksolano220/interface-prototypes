# interface-prototypes

City Strolls — a walk-planning app. Set a step goal, a time window, and what you want to see (a park, a busy street, a river skyline), then generate route options.

Route options are genuinely AI-authored: an NVIDIA-hosted Llama 3.1 8B call wrote two distinct route concepts (name, pitch, and per-stop per-time-of-day descriptions), generated once at build time and baked into the page rather than called live, so no API key sits exposed in public client-side code. Pick one and the real map appears.

Real map, real streets: Leaflet + CARTO's free dark basemap tiles, with actual walking directions from OSRM's free public routing API — no API key, no signup, nothing to configure. Falls back to a straight-line estimate if the routing service is ever unreachable.

Design: real glass panels (backdrop blur, translucency) on a black ground, a single restrained cyan accent throughout rather than a multi-color scheme, phone-mockup chrome sized to an actual iPhone 16 with a mock status bar.

Single self-contained file, `index.html`. Open it directly in a browser, or serve it from GitHub Pages.

Earlier explorations (a liquid-glass generative-UI demo, a brutalist paywall, a fixed-grammar demo across four unrelated domains, and several earlier passes at this same walk planner) live in git history if useful, but this file is the one that stuck.
