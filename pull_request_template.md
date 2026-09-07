## Bite

<!-- One sentence — the single outcome this PR delivers.
     Follow-up to a merged PR? Say so: "Follow-up to #NN (merged)". -->

## What was done

<!-- Bullets, boldest fact first. If two unrelated changes rode this
     branch, flag them separately so they can be reviewed (or split) cleanly. -->

## Evidence

<!-- Receipts, not claims. Check only what you actually ran, and state the result. -->
- [ ] Tests: `<command>` → N passed
- [ ] Gates: `<gate command>` → clean
- [ ] Driven for real: <!-- what you exercised end-to-end, and what you saw -->

## Out of scope

<!-- What this deliberately does not do, and where that work lives. -->

## Next bite

<!-- The single next bite this opens, if any. -->

## Decision

<!-- The trailer the PR-time deposit reads to draw its edges: on merge it
     records which decisions this PR touched, alongside the code at the merge
     sha and how CI went (forge-play/Forge, forge/deposit.py;
     the-forge-shape.md §12).

     The value is a PAIR ID PREFIX from the project store — 8 or more hex
     characters — not prose. The regex is
     `^\s*decision:\s*([0-9a-fA-F]{8,})\s*$`, one trailer per line; repeat the
     line for more than one, and duplicates collapse. A prefix that matches
     nothing, or matches more than one pair, is reported and skipped — never
     guessed. The model never names a decision; a regular expression does.

     No decision to point at? Delete the line. An unmatched trailer is noise
     in the deposit's report, and a blank one deposits nothing either way. -->

Decision: 
