# Theblinx Frontend

This repository now contains a polished front-end prototype for the Theblinx water monitoring project.

## Included UI

- Secure ingestion endpoint display
- Live telemetry cards for device IDs, flow, voltage, and pump current
- User dashboard with tier-based access logic (Basic / Standard / Premium)
- Operator command board with connection status and access control states
- Billing workflow for deposit, deployment balance, and monthly subscription

## Run locally

Open `index.html` directly in a browser, or serve the repo locally:

```bash
cd /path/to/Theblinx
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Files

- `index.html` — main app structure
- `styles.css` — dark executive dashboard styling
- `app.js` — telemetry simulation and dashboard interactions
