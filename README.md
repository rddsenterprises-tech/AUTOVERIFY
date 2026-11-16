# AutoVerify

Vehicle VIN and license-plate lookup interface.

## Current status
- Initial frontend prototype.
- VIN and plate input modes.
- Clearly labelled illustrative sample report.
- No live vehicle-history provider is connected yet.
- Checkout is not enabled; pricing is a UI placeholder only.

## Run locally
This is a static HTML prototype. Open `index.html` in a browser, or serve the folder with any static web server.

## Important data disclaimer
The included sample records are fictional/demo content. Do not present them as official, verified, government, insurance, auction, theft, lien, odometer, or accident records. Real lookups require a licensed data provider and appropriate legal/privacy review.

## Planned development
1. Finalize responsive UI and accessible interactions.
2. Integrate VIN decoding (e.g. a trusted decoder API).
3. Select a licensed vehicle-history data provider for supported markets.
4. Add secure backend endpoints; never expose provider secrets in browser code.
5. Add authentication, report entitlements, and payment after provider and business rules are finalized.
6. Add tests, logging, rate limits, and privacy/retention controls.

## Preview workflow
Development changes are made on `preview/initial-ui`. The `main` branch is reserved for approved production releases.
