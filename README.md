<div align="center">

# SOVA Engine

**The testing engine behind the TRUSCOR Rating.**

Closed source · used by TRUSCOR's rating team and licensed security firms · by [TRUSCOR](https://truscor.org)

</div>

---

## What it does

SOVA Engine **attacks, UI-tests and stress-tests an AI product, judges what happened, and writes everything as `.sova` evidence**: a signed, tamper-evident record of what the AI was shown, what it did and what changed.

## Where it fits in the SOVA stack

| Part | Role |
|---|---|
| **SOVA Engine** | Tests the AI product and produces `.sova` evidence |
| [O.W.L](https://github.com/TRUSCOR/O.W.L) | The measurement instrument that operates test environments and checks claims against real effects |
| [TAFAAR](https://github.com/TRUSCOR/TAFAAR) | Grades the evidence into the TRUSCOR Rating (300–900) |
| [SOVA Black Box](https://github.com/TRUSCOR/SOVA-Blackbox) | Records AI systems in production, 24x7 |
| [SOVA OSS](https://github.com/TRUSCOR/SOVA-OSS) | The free, open-source toolkit and the open `.sova` format |

## Who uses it

- TRUSCOR's rating team
- Licensed penetration-testing and security firms

## About this repository

This repository holds public information and demo material for SOVA Engine. **The engine's source code is private.** No code here comes from it.

## See the open part run today

The `.sova` evidence format and a working demo are open source:

```bash
git clone https://github.com/TRUSCOR/SOVA-OSS
cd SOVA-OSS
uv sync --locked
uv run sova demo sleeper
```

## Get rated

To have your AI product tested and rated, use [truscor.org](https://truscor.org): five fields and a short call.

---

© 2026 TRUSCOR Private Limited. All rights reserved.
