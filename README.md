## Hi, I'm Shunyang 👋

Machine Learning Scientist at [Genentech](https://www.gene.com/), South San
Francisco. I build **agentic LLM systems, verifiable RL environments, and
evaluation benchmarks** for small-molecule drug discovery — work that sits
between the experimental and computational sides of the lab.

My background is quantum chemistry (PhD, UC Davis, with Oliver Fiehn, Dean
Tantillo and Tobias Kind), so I come at molecular structure from first
principles: simulating mass spectra and reaction dynamics, then turning that
into tooling chemists actually use — metabolite identification, DMPK, and
reactive-metabolite toxicity.

**Interests:** agentic LLM systems · LLM evaluation & RL environments ·
cheminformatics · computational metabolomics · quantum chemistry

🕸️ [shunyangwang.netlify.app](https://shunyangwang.netlify.app/)

---

### Open-source work

**[rt-prediction-gnn](https://github.com/Shunyang2018/rt-prediction-gnn)** —
Graph neural networks predicting LC retention times from molecular structure, to
raise confidence in untargeted metabolomics annotations. Ten architectures
benchmarked; AttentiveFP reaches **0.334 min test MAE**, within 1.7× of the
instrument's own reproducibility floor, and runs **~120× faster per molecule**
than the descriptor pipeline it replaces. Shipped as a batch CLI and a REST API,
both containerised.
`Python · PyTorch · DGL · Docker · Flask`

**[metabolomics_pipeline](https://github.com/Shunyang2018/metabolomics_pipeline)** —
MS-DIAL post-processing: QC filtering, cross-assay sample harmonization, SIRIUS
structure elucidation, and ClassyFire/bioactivity annotation behind one CLI.
221 tests, CI on Linux, macOS and Windows.
`Python · pandas · Typer · SIRIUS · pytest`

**[EICI](https://github.com/Shunyang2018/EICI)** —
Methane chemical ionization on GC-QTOF to recover molecular ions for unknown
compounds. The automated workflow correctly recognized **86%** of 367
derivatized standards and surfaced a previously unreported `[M+TMS]⁺`
rearrangement adduct. ([Metabolites 2023](https://doi.org/10.3390/metabo13080962))

**[QCEIMS-analysis](https://github.com/Shunyang2018/QCEIMS-analysis)** ·
**[EXMD](https://github.com/Shunyang2018/EXMD)** —
Predicting electron-ionization mass spectra from quantum chemistry rather than
spectral libraries: trajectory analysis, similarity scoring against NIST, and an
excited-state molecular-dynamics algorithm coupling QCEIMS with MNDO and GAMESS.
([J Cheminform 2020](https://doi.org/10.1186/s13321-020-00470-3) ·
[Anal Chem 2022](https://doi.org/10.1021/acs.analchem.1c02838) ·
[JCIM 2022](https://doi.org/10.1021/acs.jcim.2c00597))

---

### Selected publications

- **Phytonutrients and potential health benefits of California almonds.**
  *Food Chemistry* 494:145120 (2025). [10.1016/j.foodchem.2025.145120](https://doi.org/10.1016/j.foodchem.2025.145120)
- **Automatic assignment of molecular ion species to elemental formulas in GC/methane chemical ionization accurate mass spectrometry.**
  *Metabolites* 13(8):962 (2023). [10.3390/metabo13080962](https://doi.org/10.3390/metabo13080962)
- **Quantum chemical prediction of electron ionization mass spectra of trimethylsilylated metabolites.**
  *Analytical Chemistry* 94(3):1559 (2022). [10.1021/acs.analchem.1c02838](https://doi.org/10.1021/acs.analchem.1c02838)
- **Beyond the ground state: predicting electron ionization mass spectra using excited-state molecular dynamics.**
  *JCIM* 62(18):4403 (2022). [10.1021/acs.jcim.2c00597](https://doi.org/10.1021/acs.jcim.2c00597)
- **Predicting in silico electron ionization mass spectra using quantum chemistry.**
  *Journal of Cheminformatics* 12 (2020). [10.1186/s13321-020-00470-3](https://doi.org/10.1186/s13321-020-00470-3)

---

### Toolbox

`Python` `PyTorch` `LLM agents / tool use` `RDKit` `pandas` `scikit-learn`
`DGL` `Docker` `Kubernetes` `AWS` `SLURM / HPC` `Fortran` `SIRIUS` `MS-DIAL`
