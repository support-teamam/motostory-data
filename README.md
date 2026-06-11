# motostory-data

Public dataset for **Moto Story** (Team AM): motorcycle maintenance schedules.

## Honesty contract — read this first
Every schedule here is **derived from generic interval rules, not OEM data**
(`scheduleSource: 'generic'` on every entry; the app labels them "standard
schedule"). Rules are drive-aware (chain / belt / shaft) and powertrain-aware
(EVs get no oil/valve items). Your owner's manual wins every disagreement —
especially valve-check intervals, which vary enormously by engine.

- `data/vehicles.json` — 111 popular US models, 17 makes, schema 2
- `data/manifest.json` — version + sha256, rebuilt by CI, served via Pages

Sibling repos: carstory-data · homestory-data · boatstory-data
