# Educators — LINKML

**Project:** LINKML  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/linkml/linkml.git  
**Pinned commit:** `7ca47cc273f4807908065e0023530991ab3ef94e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4feecdacbf073cb319fbdf8817ee2c33a2931a83f5bf34548290ed07183a1004`  
**Date:** October 2026

## Teaching with LINKML

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `4feecdacbf073cb319fbdf8817ee2c33a2931a83f5bf34548290ed07183a1004` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
