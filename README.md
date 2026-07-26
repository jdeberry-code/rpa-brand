# RPA Brand Assets

Company seal for Radiological Physician Associates, Inc. Stable, fetchable copies of the seal so document builds never depend on a manual upload.

## Files

rpa_seal_navy.png -- seal recolored to brand navy #1B2951. Use this one. No recoloring needed.  
rpa_seal_original.png -- source file, near-black ink. Use only if another treatment is required.

Both are PNG, 662 x 672 px, transparent outside the seal circle, opaque white inside it.

## Raw URLs

https://raw.githubusercontent.com/jdeberry-code/rpa-brand/main/rpa_seal_navy.png  
https://raw.githubusercontent.com/jdeberry-code/rpa-brand/main/rpa_seal_original.png

## Retrieval

Fetch at the start of any RPA document build. Do not ask for an upload unless the fetch fails.

mkdir -p assets && cd assets  
curl -sfLO https://raw.githubusercontent.com/jdeberry-code/rpa-brand/main/rpa_seal_navy.png  
curl -sfLO https://raw.githubusercontent.com/jdeberry-code/rpa-brand/main/rpa_seal_original.png

If the fetch fails (network restriction, repo moved), STOP and ask Jason to upload the PNG. Do not substitute, redraw, trace, or generate a placeholder seal, and do not proceed without it.
