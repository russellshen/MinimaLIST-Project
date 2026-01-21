# MinimaLIST

> Created and maintained by Russell Shen — © 2025-2026  
> Licensed under CC BY-NC-ND 4.0

## Overview

**MinimaLIST** is a minimal-sufficient abstraction framework for organizing and reasoning across complex domains.  
Its guiding principle is simple:

> *Use the smallest set of abstractions that remains expressive, rigorous, and generative.*

This repository hosts both:
- a **forward-facing, curated presentation** of the project, and
- a **backward-facing intellectual archive** documenting how it developed.

The flagship concrete project demonstrating MinimaLIST in practice is **EngLISP**.

---

## EngLISP (Flagship Project)

**EngLISP** is an intermediate language and semantic pipeline that bridges natural language and computation.

Its canonical form is a **four-stage pipeline**:
Natural Language
→ X-bar syntactic structure
→ Lisp S-expressions
→ LLVM IR

This pipeline serves as the primary pedagogical and technical explanation of EngLISP.

At a high level:
- Natural language provides human intent.
- X-bar syntax provides linguistically grounded structure.
- Lisp S-expressions provide canonical semantic form.
- LLVM IR provides executable realization.

The Lisp → LLVM boundary makes explicit the classical equivalence between
**lambda-calculus-style transformational semantics** and
**Turing-machine-style operational execution**,
without privileging either as ontologically primary.

EngLISP is presented in detail in the `/modules` folder.

---

## Project Structure

- **`/modules`**  
  Forward-facing, curated presentation of MinimaLIST and EngLISP.  
  This is the recommended entry point for readers.

- **`/appendix`**  
  Backward-facing, read-only archive containing:
  - previous Medium essays,
  - philosophical and exploratory writings,
  - and the intellectual genealogy of the project.  
  These materials inform the forward-facing presentation but are not themselves edited.

---

## Domains of Application

MinimaLIST currently focuses on four primary domains:

- Formal sciences (mathematics, computer science, AI)
- Neuroscience
- Critique of political economy
- Military science

Other experimental projects exist but are secondary to EngLISP.

---

## How to Read This Repository

- If you want a **clean, current presentation**, start in `/modules`.
- If you want **intellectual history and transparency**, consult `/appendix`.

The two are intentionally separated.

---

## License

All original content in this repository is © 2025-2026 Russell Shen and released under  
**Creative Commons BY-NC-ND 4.0**, unless otherwise noted.
