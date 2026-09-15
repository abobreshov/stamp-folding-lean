# Stamp folding in Lean: the first five counts

The non-crossing-hinge permutation model of folding a strip of n labelled stamps (OEIS A000136), stated as a decidable predicate on permutations of Fin n, with the counts 1, 2, 6, 16, 50 for n = 1..5 proved by decide.

Sources: OEIS A000136; Legendre, Foldings and meanders, arXiv:1302.2025.

The Lean files are laid out exactly as in [Lean Pool](https://github.com/lyfar/lean-pool)
(`LeanPool/StampFolding.lean` and `LeanPool/StampFolding/`), where they were authored and checked with
Lean 4.31.0-rc1 and Mathlib v4.31.0-rc1 (`lake build`, `lake exe runLinter`,
`lake exe lint-style`; no `sorry`, `axiom` or `native_decide`). This repository is the
source anchor for the Lean Pool entry; the lakefile mirrors the pool's Mathlib pin.
Licence: Apache 2.0.
