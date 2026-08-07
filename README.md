# Box Triage

Keep-or-transfer decisions for a Pokémon GO collection.

Type a species name and it tells you **KEEP** or **TRANSFER** and why, based on a
type-coverage bench (keep 3 of each core raid type, fewer for niche types) rather
than raw CP or IVs. Tracks which bench slots you've already filled, so the fourth
copy of a species comes back as a transfer automatically.

Also flags:

- the correct fast/charged moveset for each raid role, and whether a TM is needed
- legacy / Community Day moves that only an Elite TM can restore
- PvP staples that look weak by CP and should be checked on PvPoke first
- protections (shiny, lucky, shadow, costume, hundo, XXL, Best Buddy) that override any verdict

**Scan tab** does best-effort OCR on an appraisal screenshot to prefill the form.
It needs internet the first time to fetch the OCR engine, and it is not as reliable
as Poke Genie — typing three letters is usually faster. Everything else works offline.

Single-file `index.html`. State is stored in the browser via localStorage.

Live: https://lawnsplantspests-ui.github.io/pogo-triage/
