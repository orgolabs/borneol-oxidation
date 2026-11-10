<p align="center">
  <a href="https://github.com/orgolabs"><img src="https://orgolabs.github.io/shared/brand/orgolabs-wordmark.png" alt="orgolabs — organic chemistry labs" width="300"></a>
</p>

# Oxidation of Borneol to Camphor — an interactive, fact-checked explainer

> Part of **[orgolabs](https://github.com/orgolabs)** — interactive, fact-checked organic chemistry labs.
> **Live site:** https://orgolabs.github.io/borneol-oxidation/

Oxidation of the secondary alcohol **borneol** to the ketone **camphor** using **sodium hypochlorite (bleach) in acetic acid** — the oxidation half of a borneol → camphor → isoborneol redox sequence (the reduction half is the sibling [camphor-reduction](https://orgolabs.github.io/camphor-reduction/) lab). It shows *how* and *why* the reaction works: real 3D structures (PubChem + [3Dmol.js](https://3dmol.csb.pitt.edu/)), the hypochlorous-acid/alkyl-hypochlorite mechanism, why bleach is a *greener* oxidant, the procedure, and a live yield calculator.

## The chemistry in one line

Bleach + acetic acid generate HOCl, which oxidizes the 2° alcohol to the ketone:
`C₁₀H₁₈O —NaOCl / AcOH→ C₁₀H₁₆O` (loses H₂).

## Run it locally

Open `index.html`, or serve with `python3 -m http.server`. The shared engine, styles, and 2D pathway images load from https://orgolabs.github.io/shared/. The 3D geometries are shared with the sibling camphor-reduction lab.

## Credits & licensing

- Site content and code: **MIT License**.
- Molecular data: **PubChem**, U.S. National Library of Medicine — **public domain** (borneol CID 6552009, camphor CID 159055, isoborneol CID 6321405).
- 3D rendering: **3Dmol.js** (Rego & Koes, *Bioinformatics* 2015) — **BSD-3-Clause**.

> Educational summary only — not a substitute for a supervised laboratory SOP. Bleach, glacial acetic acid, acetone, and MTBE require a fume hood and appropriate PPE.
