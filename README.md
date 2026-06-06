# Hornero Insights Samples

Evidence-based research samples for complex, event-driven markets.

Hornero Insights develops research pipelines that collect, validate, reconcile, and monitor data from multiple public sources.

This repository contains public sample outputs from Hornero research products.

The goal is to demonstrate data structure, research methodology, source reconciliation, and reporting style.

---

## Research Areas

### Pharma Catalysts

Research focused on regulatory and clinical catalysts.

Sample outputs may include:

- FDA catalyst calendars
- Regulatory event briefings
- FDA Press and Advisory Committee evidence
- ClinicalTrials.gov context
- Company disclosure monitoring
- Catalyst status snapshots
- Source reconciliation reports

### Agriculture Fundamentals

Research focused on production, weather, and global commodity flows.

Sample outputs may include:

- USDA vs local source reconciliation
- CONAB, MAGyP, Bolsa and BCR comparisons
- Crop stress grids
- NDVI and vegetation monitoring
- Soil moisture context
- Weather and precipitation analysis
- WASDE revision tracking
- Production and ending-stock divergence

### Energy Physical Regimes

Research focused on physical commodity balances.

Sample outputs may include:

- EIA inventory trends
- Crude, gasoline, and distillate balances
- Crack spread monitoring
- Demand and export context
- LNG flow monitoring
- OPEC vs EIA reconciliation
- Physical regime briefings

---

## Sample Dataset

Example: Agri Crop Stress Dataset

```json
{
  "country": "ARGENTINA",
  "commodity": "CORN",
  "weather": {
    "soil_moisture_context": "dry_surface"
  },
  "production": {
    "usda_production_mmt": 59.0,
    "local_anchor_source": "MAGYP",
    "local_production_mmt": 51.69,
    "local_sources_divergence_flag": true
  }
}
```

### What This Shows

- Source reconciliation
- Official versus local production estimates
- Weather context
- Soil moisture conditions
- Export demand indicators
- Data quality flags
- Evidence-oriented research outputs

---

## Research Principles

Hornero follows a source-first methodology.

1. Collect data from public sources.
2. Preserve evidence whenever possible.
3. Validate using independent witnesses.
4. Reconcile disagreements between sources.
5. Report uncertainty and missing data.
6. Avoid invented values and unsupported conclusions.

If a source does not provide a value, Hornero reports the absence rather than estimating a replacement.

---

## Repository Structure

```text
pharma/
├── sample_catalyst_briefing.xlsx
├── sample_pharma_snapshot.json
└── sample_reconciliation.csv

agri/
├── sample_crop_stress.json
├── sample_stress_grid.xlsx
└── sample_reconciliation.csv

energy/
├── sample_physical_regime.xlsx
├── sample_energy_snapshot.json
└── sample_regime_briefing.pdf
```

---

## What Is Included

Public sample outputs.

Examples of:

- Research datasets
- Sample reports
- Example briefings
- Example spreadsheets
- Example JSON exports

---

## What Is NOT Included

This repository does **not** contain:

- Production source code
- Internal infrastructure
- Proprietary pipelines
- Internal scoring systems
- API keys
- Commercial datasets
- Private research products

---

## Not Investment Advice

The materials contained in this repository are provided solely for research, educational, monitoring, and evaluation purposes.

Nothing contained in this repository constitutes:

- Investment advice
- Financial advice
- Trading advice
- Legal advice
- Tax advice
- A recommendation to buy, sell, hold, short, or trade any security, commodity, derivative, fund, token, or financial instrument

Users are solely responsible for their own analysis, due diligence, and decisions.

---

## License

Copyright © Hornero Insights.

All rights reserved.

This repository contains public sample materials provided for evaluation and informational purposes only.

You may:

- View the contents of this repository
- Download copies for personal evaluation
- Reference the repository with attribution

You may not:

- Redistribute the materials as a commercial product
- Sell, sublicense, or resell repository contents
- Create competing commercial products using repository contents
- Repackage repository contents for commercial distribution
- Remove copyright notices

Permission for commercial use must be obtained in writing from Hornero Insights.

THE MATERIALS ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.

---

## Contact

For commercial access, partnerships, licensing inquiries, or current research products:

**Hornero Insights**

Research, not recommendations.
