# rh

This repository holds a copy of a Lean 4 project distributed as the archive `lean.tar.gz` in 14 parts.  The four-page note at <https://alpo.ge/remark.pdf> lists the parts in its first footnote.  In that note, the author states that, working with Claude, they found a proof of the Riemann Hypothesis and the Generalized Riemann Hypothesis and formalized it in Lean without assumptions.  The note does not name its author, and its PDF metadata gives a creation date of 2026-11-20.

## Provenance

This copy comes from the parts at `https://alpo.ge/lean.tar.gz.part01` through `https://alpo.ge/lean.tar.gz.part14`, downloaded on 2026-11-20 and joined in numeric order.  The directory `lean/` holds the contents of the joined archive without modification, and this README is the only added file.  The archive includes no license file.

| File | Bytes | SHA-256 |
|------|-------|---------|
| `remark.pdf` | 245,114 | `3fc97784b71ddd44ff8aa0a177e99622a1c61b13cfa843a0989ee4a7a0cfeb8d` |
| `lean.tar.gz` (joined) | 239,275,554 | `9631b4f020199e580ba86178cb56c6e9b09f690c2369a80dc4334aa93f49c7fc` |

## Status

Publishing this copy did not include building the project or reading its proofs.  The claim of a proof belongs to the note's author and has not been checked here.  The `Main` library has roots `lean/src/Statements.lean` and `lean/src/Main.lean`, which are the places to start an evaluation of what the project states and whether it depends on `sorry` or added axioms.

| Item | Value |
|------|-------|
| Lean toolchain | `leanprover/lean4:v4.33.1` |
| Mathlib | commit `0df444a360eaa60ab8c11dca51a86af692955474` |
| Lean source files | 175,187 |
| Source size | 983 MB |
