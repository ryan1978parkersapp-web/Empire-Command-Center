# Parker Empire — Command Center

Local-first web app to **manage the empire and track money**.

## What it does

- **Dashboard** — revenue KPIs, current focus (MailPilot security), quick sale log
- **Money** — revenue ledger + CSV export (stays on device)
- **Phases** — Execution Hub phases 0–7 with live status
- **Tasks** — checklist tied to phases (HMAC, inventory, domain, fulfillment)
- **Store** — your 3 active Shopify products:
  - MailPilot License — **$97**
  - Parker’s Mind Starter Pack — **$49**
  - Support Hour — **$75**

Store: `parkersapps-parkersempire.myshopify.com` (Basic App Development, USD)

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
# Python
python -m http.server 8080

# Node
npx serve .
```

Then open `http://localhost:8080`. Install as PWA from the browser menu on phone/desktop.

## Data

All sales, tasks, and phase status save to **localStorage** under `parker_empire_cc_v1`. No account required. Export CSV anytime from Money.

## Next money moves

1. Custom domain → Shopify
2. Finish MailPilot webhook security (Phase 4 checklist)
3. Digital delivery for license + starter pack
4. Booking path for Support Hour
5. Auto-import Shopify orders via webhook into this ledger

## Repo intent

Part of Parker Empire Forge. Evidence-based: log what ships, measure revenue, don’t assume systems work until verified.
