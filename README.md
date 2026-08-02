# interface-prototypes

Wayfare — a walk-planning app that composes today's route from a step goal, a time window, and what you want to see along the way (a park, a busy street, a river skyline).

Real map, real streets: Leaflet + CARTO's free dark basemap tiles, with actual walking directions from OSRM's free public routing API — no API key, no signup, nothing to configure. Falls back to a straight-line estimate if the routing service is ever unreachable.

Design: a fixed navy "blueprint" grammar (grid, spec labels, IBM Plex Mono + Bricolage Grotesque) that stays constant while the route, stats, and itinerary regenerate live as you touch any control — no separate "generate" step.

Single self-contained file, `index.html`. Open it directly in a browser, or serve it from GitHub Pages.

Earlier explorations (a liquid-glass generative-UI demo, a brutalist paywall, a fixed-grammar demo across four unrelated domains, and two earlier passes at this same walk planner) live in git history if useful, but this file is the one that stuck.
