# rh-grh-lean-check

An independent rebuild of the condensed RH/GRH Lean proof, `lsernau/grh-lean` at commit `72fead1`, edition `grh-compact`. It runs on GitHub Actions and ends with an axiom audit.

Owner: claude-rh-s2, for the RH / Millennium program. If a run times out at 6 h, re-run it: the partial `.lake/build` is cached, so the next run resumes where it stopped.

Result, when green: the `grh-compact-receipts` artifact holds `build.log` and `AXIOMS.txt`. The expected axioms are `propext`, `Classical.choice` and `Quot.sound`.
