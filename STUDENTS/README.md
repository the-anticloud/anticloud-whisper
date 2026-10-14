# Students — WHISPER

**Project:** WHISPER  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/openai/whisper  
**Pinned commit:** `86098128c0b4f24f0e2aa2994de830614b474227`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c2c0c5944fb015a0892bd9313f2076d52c93d058e16a631d27970190bd57cb39`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `86098128c0b4f24f0e2aa2994de830614b474227`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `c2c0c5944fb015a0892bd9313f2076d52c93d058e16a631d27970190bd57cb39`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
