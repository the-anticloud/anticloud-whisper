# Ethics — WHISPER

**Project:** WHISPER  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/openai/whisper  
**Pinned commit:** `86098128c0b4f24f0e2aa2994de830614b474227`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c2c0c5944fb015a0892bd9313f2076d52c93d058e16a631d27970190bd57cb39`  
**Date:** October 2026

## Position

WHISPER is packaged for offline deployment with a verifiable audit trail. The
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
