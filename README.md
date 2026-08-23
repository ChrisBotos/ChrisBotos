Computational biology researcher and MSc student in Bioinformatics & Systems
Biology (UvA/VU). I build mechanistic and inference models of RNA Pol II
transcription, and apply deep learning to multi-omics imaging.

**BSc thesis (transcription simulation, University of Crete): 10.00/10.**
MSc (Bioinformatics & Systems Biology, UvA/VU): 8.05, in progress.

**Stack across these projects:** Python, Cython, stochastic/Markov-chain
modeling, and vision transformers (DINO ViT) for image analysis.

## Now: MSc placement, Netherlands Cancer Institute (Sep 2026-Jun 2027)

Van Steensel group, Division of Gene Regulation. Extending PARM, a
deep-learning promoter-activity CNN published in Nature (doi:
10.1038/s41586-025-10093-z), to endogenous transcription in K562, benchmarked
against Activity-by-Contact. Daily supervision by Oscar Garcia Blay,
co-supervised by Vinicius Franceschini-Santos. The analysis pipeline
(`metron`, private) already runs the raw qPRO-seq mapping, GENCODE-resolved
window counting, and a PARM-reproduction step ahead of the official start. It
already carries the project's reproducibility scaffolding: every input traced
to a checksummed manifest, every threshold preregistered ahead of the
placement's data.

## Ongoing: Research Assistant, IMBB-FORTH (Sep 2023-present)

Under Matthieu Lavigne, building a four-part framework that simulates, solves,
and infers RNA Pol II transcription kinetics end to end - continuing a BSc
thesis that modeled transcription in silico (University of Crete):

- **POLYARIS**: stochastic simulation of Pol II via a TASEP (Totally Asymmetric
  Simple Exclusion Process) model with spatial exclusion, pausing, and obstacle
  interactions, run as a continuous-time Markov chain (Gillespie algorithm),
  Cython-accelerated.
- **KINEMA**: closed-form Markov-chain solutions for Pol II initiation
  kinetics - the analytical counterpart to POLYARIS's simulation - including
  "cascade" transitions for packed-polymerase trains. Co-authored with
  Michalis Loulakis (NTUA).
- **GENEFIT**: recovers transcription-kinetic parameters from ChIP-seq/PRO-seq/
  mNET-seq features by nested brentq root inversion plus joint Poisson profile
  MLE, no stochastic search.
- **SCAN**: downstream statistical analysis and figure generation across the
  suite.

POLYARIS, KINEMA, and GENEFIT each carry an automated pytest suite run on every
change; GENEFIT is additionally validated against synthetic ground-truth data
before being applied to real sequencing data.

This research is ongoing; the code is private, with
`Private_Projects_Showcase` (pinned below) marking that it exists. Happy to
talk through it directly on request.

## Before: LUMC, spatial multi-omics

Ahmed Mahfouz's group, Human Genetics. Cell segmentation and vision
transformers on tissue imaging:

- **vitseg**: unsupervised tissue-region discovery in kidney microscopy, using
  DINO ViT-S/16 self-supervised features clustered with MiniBatchKMeans.
- **ATLAS-Cellpose**: adaptive tiled segmentation wrapper around Cellpose,
  merging results across tiles via a four-step algorithm.

Co-author, Manzato et al., "Image-guided alignment of consecutive multi-modal
tissue slides" ([bioRxiv](https://doi.org/10.64898/2025.12.02.690676), 12/2025).

---

[ORCID](https://orcid.org/0000-0002-4228-8909) ·
[LinkedIn](https://www.linkedin.com/in/christos-botos-2369hcty3396/)
