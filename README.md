# interface-prototypes

Four self-contained HTML prototypes exploring where GUI is heading, built out of a conversation tracing interface history (CLI → GUI → touch → voice → spatial → agentic/generative UI) into a question about how a designed object expresses "a view from somewhere" instead of trying to be neutral.

Each file is a single, dependency-free HTML page (fonts embedded as base64, no external requests) — open any of them directly in a browser.

## The four objects

**`glass-intent.html`** — Liquid glass material over a generative-UI interaction: type an intent (or tap a suggestion) and the interface builds a different-shaped surface around it live. The trend-report version: synthesizes 2026's liquid glass + generative UI conversation, deliberately took no strong stance.

**`no-asterisks.html`** — A mobile paywall screen with the opposite stance: maximal, loud, brutalist. Every renewal date and fee is printed as loud as the price; the default plan is the one that makes the company *less* money, on principle. The point of view: transparency as an ethic, refusal as a design tool.

**`fixed-grammar.html`** — The actual thesis, made concrete: four unrelated domains (weather, a dinner reservation, a boarding pass, a houseplant) rendered through one identical, never-moving template. Same slot positions, same button, only the content changes. This is the bet on where interfaces are actually heading — not a new visual skin, but a stable grammar with generated filling.

**`wayfare.html`** — A working walk-planning app: set a step goal, pick a time window, tap illustrated stop cards (a park, a street, a river skyline) to build today's route. A live accordion itinerary and sticky CTA track distance, steps, and time against the goal. Styled to match a specific clean travel-app reference (photo-card layout, pill tabs, floating bottom nav) rather than a generic take — went through an earlier holographic-HUD pass first, kept in git history.

## Notes

- All four commit to a single visual theme (they don't adapt to OS light/dark mode) — each is a deliberate, atmospheric world, not a utility that needs to fit every context.
- `wayfare.html` and `no-asterisks.html` are designed mobile-first (open on a phone, or view the desktop preview inside the phone-frame mockup).
- Route/pricing/waypoint data in all four is illustrative, not live — no real APIs, no real mapping data.
