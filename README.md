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

## Disclaimer

This dataset is provided for **general informational purposes only**. The
intervals, schedules, and cost figures are **typical-case estimates** — many are
derived from generic, rule-based heuristics rather than manufacturer or expert
data, and some descriptions are produced with the help of automated (AI) tools.

It is **not** professional, medical, veterinary, or manufacturer advice. Always
verify against your owner's manual or a qualified mechanic before acting. The data is provided "as is", without
warranty of any kind, and you use it at your own risk. Team AM is not affiliated
with any manufacturer or brand referenced.

Full terms: https://teamam.org/terms
