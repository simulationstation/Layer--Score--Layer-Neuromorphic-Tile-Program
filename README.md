# Layer-Score-Layer Neuromorphic Tile Program

A complete set of operational guides for fabricating neuromorphic computing tiles using memristive crossbar arrays in shared/professional cleanroom facilities.

## Overview

This repository contains 16 standalone LaTeX documents covering the full fabrication and characterization workflow for neuromorphic tiles—from program planning through release engineering. The guides address facility protocols, process recipes, design rules, device characterization, array integration, and reproducibility practices.

## Guide Index

| # | Title |
|---|-------|
| 00 | Program Framing and Success Metrics |
| 01 | Facility Access and Operating Model |
| 02 | Contamination Control and Materials Governance |
| 03 | Design Toolchain, Layer Maps, and DFM Rules |
| 04 | Standard Process Traveler and Run Logging |
| 05 | Baseline Deposition: Electrodes and Dielectrics |
| 06 | Maskless Lithography Workflow |
| 07 | Lift-off vs Etch Decision Tree |
| 08 | Planarization Strategy |
| 09 | Scoring Runbook (Localized Fine Features and Repair) |
| 10 | Single-Device Characterization Suite |
| 11 | Neuron Behavior Bring-up |
| 12 | Array Design and Sneak-Path Management |
| 13 | Compact Model Calibration and Hardware-in-the-Loop Simulation |
| 14 | Packaging, Board Integration, and Tile Demonstration |
| 15 | Release Engineering for Open-Source Reproducibility |

## Compiling the Documents

Each `.tex` file is standalone and requires only standard LaTeX packages.

### Option 1: Overleaf (Free, No Installation)

1. Go to [overleaf.com](https://www.overleaf.com) and create a free account
2. Click **New Project** → **Upload Project**
3. Upload any individual `.tex` file (or zip the entire repository)
4. Overleaf will compile automatically with PDFLaTeX

### Option 2: Local Compilation

```bash
pdflatex -interaction=nonstopmode -halt-on-error Guide00_Program_Framing_and_Success_Metrics.tex
```

Requires a TeX distribution such as TeX Live, MiKTeX, or MacTeX.

## Notes

- These are operational/governance guides intended for use in professional or shared cleanroom facilities
- All processes assume proper safety controls and equipment training are in place
- Documents are versioned independently; check the header of each PDF for revision info

## License

Open research draft. See individual documents for specific terms.
