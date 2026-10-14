# Students — VAPR_BALLISTICS_PRIOR_DOCS

**Project:** VAPR_BALLISTICS_PRIOR_DOCS  
**Category:** ARTILLERY_MANUFACTURING  
**Upstream:** https://github.com/robsdevcraft/vapr-ballistics  
**Pinned commit:** `44b19e7b7749af39ddfff1f2073c58bb4c47e865`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b1403b63b05724fca84bdcbc6d53a8b1faf1821fcd5140894a6692b229c43b1c`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `44b19e7b7749af39ddfff1f2073c58bb4c47e865`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `b1403b63b05724fca84bdcbc6d53a8b1faf1821fcd5140894a6692b229c43b1c`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
