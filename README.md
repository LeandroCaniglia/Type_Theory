![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)

# Homotopy Type Theory
### A Detailed Exposition of the HoTT Book

[�� Read the compiled PDF](https://github.com/LeandroCaniglia/Type_Theory/blob/main/Type_Theory.pdf) | [�� Reflections on a Journey Through HoTT](https://leandrocaniglia.github.io/hott-notes)

---

Welcome to this repository containing a detailed, mathematically rigorous set of personal notes and expositions on **Homotopy Type Theory (HoTT)** and constructive type theory.

This project bridges the gap between the intuitive, high-level prose of the standard *HoTT Book* and the explicit, foundational rules of dependent type theory.

## �� About the Project

These notes serve as a structured companion for anyone exploring univalent foundations. Instead of taking proofs "as given" or relying heavily on informal pattern-matching syntax, this exposition prioritizes **reconstructing intermediate mathematical steps** and **formalizing proofs using primitive eliminators**.

### Core Highlights & Themes Covered:
* **The Geometry of Identity:** Unpacking path induction, transport, and the fundamental action of functions on paths ($\text{ap}_f$).
* **Univalent Foundations:** Examining the precise mechanics of the Univalence Axiom, its role in proving function extensionality, and the equivalence of path spaces.
* **Generalizations of Induction:** Tracing the boundaries of inductive definitions from foundational $W$-types up to advanced concepts like mutual inductive types and inductive-inductive definitions.
* **A Categorical Lens on Equality:** Studying both local and global *Identity Systems* and understanding path induction as a type-theoretic manifestation of the **Yoneda Lemma**.

## �� Philosophy of the Exposition

Unlike traditional textbooks that gloss over definitional reductions, this text takes a hands-on approach:
1. **No Hand-Waving:** Informal pattern-matching is systematically translated into explicit constructions using primitive eliminators (such as $\text{ind}_W$ and $\text{ind}_{\mathbf{1}+A}$).
2. **Judgmental Verification:** We explicitly verify that the expected computation rules hold *judgmentally* (definitionally) rather than just propositionally.
3. **Self-Contained Exercises:** Key exercises from the HoTT literature are rewritten to be completely self-contained, specifying precise type signatures and eliminating ambiguous structural assumptions.

---

## �� License & Attribution

This work is based on and expands upon *Homotopy Type Theory: Univalent Foundations of Mathematics* (2013) by **The Univalent Foundations Program**, which is licensed under [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/).

These notes are released under the **Creative Commons Attribution-ShareAlike 4.0 International License ([CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/))**.

---
*This repository represents an active, ongoing effort to map the beautiful landscape where topology, category theory, and computer science meet.*