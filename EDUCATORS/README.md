# Educators — WHISPER

**Project:** WHISPER  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/openai/whisper  
**Pinned commit:** `86098128c0b4f24f0e2aa2994de830614b474227`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c2c0c5944fb015a0892bd9313f2076d52c93d058e16a631d27970190bd57cb39`  
**Date:** October 2026

## Teaching with WHISPER

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `c2c0c5944fb015a0892bd9313f2076d52c93d058e16a631d27970190bd57cb39` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
