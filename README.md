Computational biology researcher and MSc student in Bioinformatics & Systems
Biology (UvA/VU). I build mechanistic and inference models of RNA Pol II
transcription, and apply deep learning to multi-omics imaging.

## Now: MSc placement, Netherlands Cancer Institute

Van Steensel group, Division of Gene Regulation. Extending PARM, a
deep-learning promoter-activity CNN published in Nature (doi:
10.1038/s41586-025-10093-z), to endogenous transcription in K562, benchmarked
against Activity-by-Contact. Daily supervision by Oscar Garcia Blay,
co-supervised by Vinicius Franceschini-Santos.

## Ongoing: Research Assistant, IMBB-FORTH

Under Matthieu Lavigne, building a four-part transcription-kinetics framework:

- **POLYARIS**: stochastic simulation of Pol II via a TASEP (Totally Asymmetric
  Simple Exclusion Process) model with spatial exclusion, pausing, and obstacle
  interactions, run as a continuous-time Markov chain (Gillespie algorithm),
  Cython-accelerated.
- **KINEMA**: closed-form (non-simulated) stationary-probability solutions for
  Markov-chain models of Pol II initiation kinetics, including physically
  motivated "cascade" transitions for packed-polymerase trains. Co-authored
  with Michalis Loulakis (NTUA).
- **GENEFIT**: recovers transcription-kinetic parameters from ChIP-seq/PRO-seq/
  mNET-seq features by nested brentq root inversion plus joint Poisson profile
  MLE, no stochastic search.
- **SCAN**: downstream statistical analysis and figure generation across the
  suite.

A first-author manuscript on this work is in prep; the code is private.
`Private_Projects_Showcase` (pinned below) is a pointer, not a code repo - it
marks that this work exists. Happy to talk through it directly on request.

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
