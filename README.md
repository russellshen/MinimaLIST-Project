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
→ LLVM IR.

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
  Backward-facing, read-only archive containing sources of intellectual provenance that predate or exist outside this GitHub repository:
  - Previous Medium essays,
  - Philosophical and exploratory writings,
  - Miscellaneous external notes,
  - And the intellectual genealogy of the project, mostly consisting of ChatGPT logs.  
  These materials inform the forward-facing presentation but are not themselves edited, nor were they intended for online publication at the time of their composition.
  Historical versions of files tracked within this repository are preserved by GitHub’s version control; the appendix exists specifically to retain external sources that would not otherwise
  be captured by the repository’s commit history.

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

The two are intentionally separated, with the expectation that people would first want to develop intellectual interest in the MinimaLIST
project through the exposition in `/modules` before venturing into `/appendix` to understand how the project evolved into its present-day
state. 

---

## License and Commercial Use

All original content in this repository is © 2025-2026 Russell Shen and is licensed under the  
**Creative Commons Attribution–NonCommercial–NoDerivatives 4.0 International (CC BY-NC-ND 4.0)** license, unless otherwise noted.

This license permits non-commercial use with attribution and prohibits both commercial use and derivative works without explicit permission.

[![License: CC BY-NC-ND 4.0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

See [`LICENSE`](./LICENSE) and [`NOTICE`](./NOTICE) for details.

---

### Commercial and Proprietary Licensing

Commercial use, proprietary use, or use in closed-source or revenue-generating projects is **not granted** under the CC BY-NC-ND 4.0 license.

Parties interested in licensing this work for commercial or proprietary purposes may contact:

**Russell Shen**  
📧 *russellshen7@gmail.com*

Licensing terms, scope, and compensation are subject to separate negotiation and are granted only by explicit written agreement.
