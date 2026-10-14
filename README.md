# BillShield

**Give AI experiments a spending seatbelt.** BillShield is a cost-guardrail sandbox for teams building API-powered demos. It lets a user set a budget and warning point, then see how a proposed run might affect a project cap.

## Try it

Open `index.html` in a modern browser. Set a cap and warning threshold, enter a cost estimate, and choose **Simulate one run**. The hard stop blocks any demo run that would exceed the remaining cap. Data is stored in the browser's local storage.

## The demo

- User-controlled monthly cap and warning threshold
- Per-run estimate input with a simulated hard stop
- Usage summary and reset control
- No account, API key, or network request

## Scope and limitations

This prototype does not know provider prices, call an API, inspect usage, or prevent a real bill. The estimate is supplied by the user and is only for the local simulation. Connect provider billing data and enforce limits at a trusted service boundary before relying on a production guardrail.

## Inspiration

The project follows the small, demoable MVP format from [geekedparker/hackathon-projects](https://github.com/geekedparker/hackathon-projects) and problem-centered briefs from [willwoodward/hackathon-ideas](https://github.com/willwoodward/hackathon-ideas). It is an original implementation; no source code was copied.

## Next steps

Add provider-neutral usage imports, configurable per-project policies, and alerts with explicit user consent. Validate cap enforcement against actual provider semantics before presenting it as protection.
