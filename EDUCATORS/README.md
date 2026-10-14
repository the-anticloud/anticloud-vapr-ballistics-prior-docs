# Educators — VAPR_BALLISTICS_PRIOR_DOCS

**Project:** VAPR_BALLISTICS_PRIOR_DOCS  
**Category:** ARTILLERY_MANUFACTURING  
**Upstream:** https://github.com/robsdevcraft/vapr-ballistics  
**Pinned commit:** `44b19e7b7749af39ddfff1f2073c58bb4c47e865`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b1403b63b05724fca84bdcbc6d53a8b1faf1821fcd5140894a6692b229c43b1c`  
**Date:** October 2026

## Teaching with VAPR_BALLISTICS_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `b1403b63b05724fca84bdcbc6d53a8b1faf1821fcd5140894a6692b229c43b1c` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
