# AutoVerify

A responsive vehicle lookup and vehicle-history report website.

## Project structure

- `index.html` — public-facing website, VIN and registration lookup interface, report package presentation.
- `admin.html` — separate operations dashboard interface.

## Current integration status

- VIN and registration input validation: available.
- Vehicle-history data provider: not connected.
- Secure checkout and payment processing: not connected.
- Customer order database: not connected.
- Tawk.to live chat: awaiting the client's Property ID and Widget ID.
- Administrator authentication: must be implemented before private operational data is stored.

## Run locally

Open `index.html` in a browser, or serve the project directory with a static web server.

## Data and service requirements

The current lookup experience validates the submitted input format only. It does not retrieve official vehicle records. The report layout is illustrative and must not be represented as verified vehicle history.

Before accepting paid orders:
1. Select a licensed vehicle-history data provider and confirm supported countries and coverage.
2. Implement secure server-side API endpoints; never expose provider credentials in browser code.
3. Implement administrator authentication and role-based authorization.
4. Connect a secure payment gateway and verify payment status server-side.
5. Connect order storage, report entitlements, and report delivery.
6. Publish complete privacy, terms, refund, and customer support policies.
7. Configure Tawk.to using the client's account identifiers.
8. Test the full customer and administrator journeys before production release.

## Branch workflow

UI/UX work is developed on preview branches. The `main` branch is reserved for approved production releases.
