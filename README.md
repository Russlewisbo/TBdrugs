# Anti-Tuberculosis Drugs — Lecture Package

A 1.5-hour lecture on the pharmacology of antituberculous drugs for postgraduate
infectious diseases specialists (University of Padova).

## Contents

- `anti-tb-drugs-slides.qmd` — Quarto RevealJS deck (~72 content slides + section dividers)
- `anti-tb-drugs-webpage.qmd` — Quarto HTML lecture-notes page (full reference)
- `anti-tb-drugs-references.bib` — 85 BibTeX entries (chapter refs + PubMed-verified modern additions)
- `anti-tb-drugs-images/` — institutional logo (DMM_newlogo.png)
- `custom.scss`, `diagnostic-microbiology-and-infectious-disease.csl`, `_extensions/fontawesome/` — theme/render assets

## Source

Backbone: Griffith, Brown-Elliott & Wallace, "Antimycobacterial Agents" (Ch. 38,
*Mandell, Douglas, and Bennett's Principles and Practice of Infectious Diseases*).
Supplemented with current guidance and pivotal trials verified via PubMed:
Saukkonen 2025 (ATS/CDC/ERS/IDSA update), WHO 2022 Module 4, Nahid 2019 (DR-TB),
Study 31 (Dorman 2021), Nix-TB, ZeNix, TB-PRACTECAL (BPaLM), and endTB.

Modern-additions bib entries are flagged with `% VERIFIED (PubMed)` comments and PMIDs.

## Rendering

Render in RStudio / Quarto (`quarto render`). No Quarto engine was available in the
build sandbox, so a first local render is recommended to confirm layout. Structural
checks passed: BibTeX parses (85 unique keys, balanced braces), YAML is valid, and
every `[@key]` used resolves to a bib entry.

## Notes on currency

The source chapter predates BPaL/BPaLM and the 2021 XDR redefinition. The lecture
foregrounds the current framework (all-oral 6-month BPaLM as preferred RR/MDR-TB
therapy, the 4-month DS-TB regimen, revised resistance definitions) while retaining
the chapter's drug-by-drug pharmacology. A brief NTM section is included at Russ's
request.
