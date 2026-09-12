# TARGET: today's build

- **Thing:** A one-page SLO bike-route explorer with a route list; selecting a route updates its details.
- **Audience:** A rider planning a local San Luis Obispo ride and comparing distance, climbing, and route character.
- **Requirements:** One working route-selection interaction. The selected route’s distance, elevation, and a short description are clear.
- **Guardrails:** Static browser code only; no Strava connection, accounts, private activities, or live route data. Route entries are clearly labeled “sample routes.” Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A clean, map-inspired interface with a dark coastal-green route panel and high-contrast lime selection state.
- **Test:** I can select each sample route, see its details change, and verify the “sample routes” label is always visible. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
