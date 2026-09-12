# TARGET: today's build

- **Thing:** A one-page SLO bike-route explorer with a route list; selecting a route updates its details and map line.
- **Audience:** A rider planning a local San Luis Obispo ride and comparing distance, climbing, route character, and shape.
- **Requirements:** One working route-selection interaction. The selected route’s distance, elevation, a short description, and its GPX-derived map line are clear.
- **Guardrails:** Static browser code only; no Strava connection, accounts, live data, or private activities. The site may display only the two user-provided GPX routes approved for publication: Turri and Bootloop. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A clean, map-inspired interface with a dark coastal-green route panel and high-contrast lime selection state.
- **Test:** I can select Turri and Bootloop, see the details and route line change, and see the source label. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
