# Learning Math with AI

*A living collection of mathematics notes developed through interactive study with AI.*

## About

This repository documents my self-directed study of mathematics, from rigorous foundations to advanced topics. AI serves as an interactive tutor, a partner for checking proofs and counterexamples, and an assistant for turning understanding into concise LaTeX notes.

The goal is **to learn mathematics on its own terms**—not to force every concept into an AI or machine-learning application.

## Learning approach

- **Motivation before formalism:** understand what problem a definition solves and why its assumptions matter.
- **Intuition with rigor:** connect definitions, examples, counterexamples, theorems, and proofs.
- **Think structurally:** distinguish mathematical objects, additional structures, structure-preserving maps, and the properties they enable.
- **Active verification:** question arguments, work through proofs, and treat AI-generated explanations as fallible.
- **Concise notes:** record what is worth remembering, rather than archiving full conversations.

## Study workflow

1. Follow a modular learning plan (roughly **one module per day**, adjusted to understanding).
2. Study an AI-guided exposition, asking questions whenever a concept is unclear.
3. Reconstruct definitions, arguments, and examples in my own words.
4. Resolve gaps through proofs, counterexamples, and discussion.
5. Distill the material into **English LaTeX notes**, compile with `pdflatex`, and version the results here.

## Current curriculum

### Stage 1 — Real Analysis Basics + Measure-Theoretic Probability

| Module | Topic |
| --- | --- |
| 01 | Proof Language, Sets, Sequences, and limsup/liminf |
| 02 | Metric Spaces and Function Convergence |
| 03 | Sigma-Algebras and Measurable Spaces |
| 04 | Measures and Lebesgue Measure |
| 05 | Measurable Functions |
| 06 | Lebesgue Integration |
| 07 | Monotone Convergence, Fatou's Lemma, and Dominated Convergence |
| 08 | Lp Spaces and Fundamental Inequalities |
| 09 | Product Measures, Tonelli, and Fubini |
| 10 | Probability as Measure Theory |
| 11 | Independence as Independence of Information |
| 12 | Modes of Convergence of Random Variables |
| 13 | Borel–Cantelli Lemmas and Laws of Large Numbers |
| 14 | Radon–Nikodym Theorem and Change of Measure |
| 15 | Conditional Expectation and a Bridge to Martingales |

The longer-term learning path is:

**Real analysis → Measure theory → Measure-theoretic probability → Martingales → Brownian motion → Itô calculus → Stochastic differential equations.**

Other areas of interest include functional analysis, high-dimensional probability, random matrix theory, numerical analysis, optimal transport, and category theory.

## Notes and compilation

Notes are written in LaTeX, with an emphasis on key definitions, important proofs, illustrative examples, and conceptual insights. Each module may have a `.tex` source and a compiled `.pdf`.

To compile a note locally:

```bash
pdflatex Module_1_Notes.tex
```

The repository will grow incrementally as new modules are studied and notes are refined.

---

*AI helps accelerate exploration; mathematical understanding and verification remain the responsibility of the learner.*
