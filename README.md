## Hi, I'm Shunyang 👋

Computational scientist at [Brightseed](https://www.brightseedbio.com/), working
where mass spectrometry meets machine learning. I build the tooling that turns
raw LC-MS/MS and GC-MS data into identified compounds — QC pipelines, structure
elucidation workflows, and models that predict what the instrument should have
seen.

**Interests:** metabolomics · cheminformatics · quantum chemistry · graph neural networks

🕸️ [shunyangwang.com](https://shunyangwang.com/)

---

### What I'm working on

**[rt-prediction-gnn](https://github.com/Shunyang2018/rt-prediction-gnn)** —
Graph neural networks predicting LC retention times from molecular structure, to
raise confidence in untargeted metabolomics annotations. Benchmarked ten
architectures; AttentiveFP reaches **0.334 min test MAE**, within 1.7× of the
instrument's own reproducibility floor, and runs **~120× faster per molecule**
than the descriptor pipeline it replaces. Shipped as a batch CLI and a REST API,
both containerised.
`Python · PyTorch · DGL · Docker · Flask`

**[metabolomics_pipeline](https://github.com/Shunyang2018/metabolomics_pipeline)** —
MS-DIAL post-processing pipeline: QC filtering, cross-assay sample
harmonization, SIRIUS structure elucidation, and ClassyFire/bioactivity
annotation, behind one CLI. Tested on Linux, macOS and Windows.
`Python · pandas · Typer · SIRIUS · pytest`

**[EICI](https://github.com/Shunyang2018/EICI)** —
Methane chemical ionization on GC-QTOF to recover molecular ions for unknown
compounds. An automated pattern-analysis workflow correctly recognized **86%**
of 367 derivatized metabolite standards, and surfaced a previously unreported
`[M+TMS]⁺` rearrangement adduct.

**[QCEIMS-analysis](https://github.com/Shunyang2018/QCEIMS-analysis)** ·
**[EXMD](https://github.com/Shunyang2018/EXMD)** —
Quantum-chemical simulation of electron-ionization mass spectra: trajectory
analysis, spectral similarity scoring against NIST, and excited-state molecular
dynamics coupling QCEIMS with MNDO and GAMESS.

---

### Toolbox

`Python` `PyTorch` `DGL / dgl-lifesci` `RDKit` `pandas` `scikit-learn`
`Docker` `SLURM / HPC` `Fortran` `SIRIUS` `MS-DIAL`
