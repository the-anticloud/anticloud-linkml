# Students — LINKML

**Project:** LINKML  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/linkml/linkml.git  
**Pinned commit:** `7ca47cc273f4807908065e0023530991ab3ef94e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4feecdacbf073cb319fbdf8817ee2c33a2931a83f5bf34548290ed07183a1004`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `7ca47cc273f4807908065e0023530991ab3ef94e`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `4feecdacbf073cb319fbdf8817ee2c33a2931a83f5bf34548290ed07183a1004`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
