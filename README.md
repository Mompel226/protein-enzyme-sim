# Protein & Enzyme Lab

An interactive simulation for **IB Biology SL — B1.2 Proteins and C1.1 Enzymes** (first assessment 2025). Single self-contained HTML file; no installation, no dependencies.

**Run it:** open `index.html`, or use the GitHub Pages link for this repository.

## Mode 1 · Build a polypeptide (B1.2.1–B1.2.2)

- A partly finished maltase chain; the **gene dictates the order** of the last four amino acids (Ser–Cys–Asp–Lys). Wrong amino acid → rejected, with the reason.
- **Drag** the amino acid to the chain's carboxyl end, then — in a large close-up — **click the two atoms that leave as water**: the chain's carboxyl –OH and the newcomer's amine –H. Wrong atoms (the double-bonded O, the R-group, the wrong end) are refused with an explanation.
- Watch the condensation slowly: water forms and leaves, the C–N **peptide bond** draws in, the word equation and the H₂O counter update.
- Fold the finished chain: 3 hydrogen bonds, 1 ionic bond (Asp⁻·Lys⁺), 1 disulfide (Cys–Cys), and a hydrophobic core tucked **inside** the fold. Then send *your* maltase into the lab.

## Mode 2 · Enzyme lab (C1.1 · B1.2.5)

- **Amylase** (starch → maltose, one maltose per binding), **maltase** (maltose → glucose + glucose), **starch synthase** (builds starch from glucose by condensation), and a **competitive inhibitor** of amylase.
- Water is explicit: droplets fly **in** for hydrolysis and **out** for condensation, with running counts.
- **Temperature** and **pH** sliders: heat raises collision speed and vibration until weak bonds snap (staggered, weakest first); pH flips R-group charges and breaks ionic bonds. Mild pH shifts are reversible; extremes and heat damage are **permanent** — cooling never refolds a cooked enzyme. The covalent disulfide survives both.
- **Under the microscope:** click any enzyme to magnify it — every hydrogen bond, the ionic bond, the disulfide and the hydrophobic core are drawn, labelled, and tracked live (intact/broken), with a reactions-catalysed counter.
- Live **concentration–time graph** (starch/maltose/glucose) with hover readout, timer, pause, speed and reset.

## Scientific honesty

The **?** button in the app lists exactly what is accurate (bond types, mechanisms, water bookkeeping, permanence of denaturation) and what is deliberately simplified (16-bead cartoon enzymes vs ~500 amino acids; short straight starch; one-maltose-per-cut amylase; starch synthase without its real ADP-glucose/ATP cost). Salts are omitted intentionally — the IB syllabus names pH and temperature.

---

Made for NLCS Jeju Biology. Built with plain HTML5 canvas; works offline once loaded.
