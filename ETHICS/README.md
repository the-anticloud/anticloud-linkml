# Ethics — LINKML

**Project:** LINKML  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/linkml/linkml.git  
**Pinned commit:** `7ca47cc273f4807908065e0023530991ab3ef94e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4feecdacbf073cb319fbdf8817ee2c33a2931a83f5bf34548290ed07183a1004`  
**Date:** October 2026

## Position

LINKML is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
