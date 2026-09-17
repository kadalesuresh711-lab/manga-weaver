# Roadmap

- [x] Clone sparkle-glm-forge into this project and install dependencies
- [x] Store all Pixazo keys + Z.ai key as encrypted secrets (never in code)
- [x] Prompt rebuild: one identity line per character, location/action first,
      candid staging, sheet/portrait guards, cross-batch continuity
- [x] Fix Scene rewrites composition; Reroll only changes the seed
- [x] Automatic image review with GLM-4.6V-Flash (sketch / sheet / wrong scene /
      blank background / front-facing / duplicate / text) + one corrective redraw
- [x] Fix long-run quality threshold: global verification numbering, queued image
      reviews, independent review cooldown, and rejection of known-bad redraws
- [x] Lock the main character as an unmarried 23-year-old adult man in every panel
- [x] Stop twin/duplicate figures: a character's repeated description right after
      their name is collapsed, so each person is described exactly once
- [x] Clean age wording ("a 60-year-old man", not the whole look sentence)
- [x] Wordless-picture rule stated early, so signage/captions stop appearing
- [ ] Reference-image character locking — not possible on Flux.1 Schnell (text-only);
      needs an image model with reference/character conditioning
- [ ] Run the complete 00:00–05:05 script and verify every image against its
      exact timestamped line and final renderer prompt; rerun every mismatch
