# EEG-Based Motor Imagery BCI Algorithms and Technologies: A Review

**A comprehensive review of signal-processing algorithms, hardware platforms, and emerging technologies for EEG-based motor imagery brain–computer interfaces.**

**Manuscript status:** Preprint — submitted to *IEEE Access* for consideration.

[Read the preprint (PDF)](./BCI_Review_arXiv_preview.pdf) · [Author's GitHub profile](https://github.com/mhkghamsari)

> **arXiv link:** Add the verified arXiv abstract URL here when available.  
> This README describes the uploaded preprint; it does not claim that the manuscript has been accepted or published by IEEE.

## Authors

- **Mohammad Hossein Koohi Ghamsari** — Sharif University of Technology
- **Seyede Fatemeh Ghamkhari** — KTH Royal Institute of Technology
- **Siavash Bayat** — Sharif University of Technology
- **Ahmed Hemani** — KTH Royal Institute of Technology

## Overview

Electroencephalography (EEG)-based motor imagery brain–computer interfaces (MI-BCIs) translate imagined movements into commands for external devices without requiring physical movement. Their potential applications include assistive technologies, neuroprosthetics, and motor rehabilitation.

This review brings together the **software and hardware perspectives** of MI-BCI development. It examines the complete signal-processing pipeline, benchmark datasets, classical and AI-based decoding algorithms, embedded implementations, and technologies that could support more practical wearable and real-time systems.

The paper also discusses a **conceptual next-generation wearable, edge-processing MI-BCI system-on-chip (SoC) architecture**. This is a proposed framework, *not* a fabricated or quantitatively validated chip.

## Topics Covered

| Area | Coverage |
| --- | --- |
| MI-BCI fundamentals | EEG acquisition, sensorimotor rhythms, motor imagery, system architecture, and feedback |
| Signal processing | Preprocessing, artifact removal, feature extraction/selection, and classification |
| AI-based decoding | Machine learning, deep learning, CNNs, recurrent models, transformers, and related approaches |
| Benchmarking | Public MI datasets, evaluation protocols, and reported performance metrics |
| Hardware | Embedded implementations, SoCs, ASICs, FPGAs, hardware accelerators, and low-power design |
| Converging technologies | Wearable EEG, edge processing, IoT, energy harvesting, and AR/VR |
| Open challenges | Signal quality, non-stationarity, cross-subject generalization, calibration, latency, cost, and usability |

## Review Methodology

The literature search covered **January 1, 2014–July 1, 2026**, using IEEE Xplore, PubMed, ScienceOpen, Semantic Scholar, Scopus, Web of Science, and Google Scholar.

The manuscript reports the following screening process:

| Stage | Number of studies |
| --- | ---: |
| Unique records after deduplication | 1,247 |
| Excluded during title/abstract screening | 349 |
| Full texts assessed | 898 |
| Excluded after full-text assessment | 152 |
| Eligible studies in the literature corpus | 746 |
| Selected for detailed analysis in this preprint | 324 |

Search strings, eligibility criteria, screening, quality assessment, and data-extraction procedures are provided in **Section II** of the paper.

## Paper Organization

1. **Introduction** — Motivation and scope of EEG-based MI-BCI research.
2. **Review Methodology** — Research questions, search strategy, and study selection.
3. **BCI Modalities** — Electrical, magnetic, and metabolic approaches.
4. **EEG-Based MI-BCI Systems** — Principles, acquisition, processing, and feedback.
5. **MI-BCI Signal Processing Algorithms** — Classical and AI-based software methods and hardware implementations.
6. **Converging Technologies** — Wearable devices, embedded/edge systems, connectivity, and immersive technologies.
7. **Proposed Next-Generation System** — Conceptual MI-BCI architecture and integrated processing framework.
8. **Discussions** — Synthesis of findings, challenges, and potential solutions.
9. **Conclusion** — Research directions for practical MI-BCI systems.

## Repository Contents

```text
.
├── README.md
└── BCI_Review_arXiv_preview.pdf
```

This is a **paper repository**, not an implementation repository. The uploaded manuscript is a literature review; this repository does not currently provide executable code, trained models, experimental datasets, or a validated SoC implementation.

## Citation

If this review supports your research, please cite the preprint or its eventual published version. Update the citation below when a verified arXiv identifier, DOI, or final publication record becomes available.

```bibtex
@misc{koohighamsari2026eeg,
  author = {Koohi Ghamsari, Mohammad Hossein and
            Ghamkhari, Seyede Fatemeh and
            Bayat, Siavash and
            Hemani, Ahmed},
  title  = {EEG-Based Motor Imagery BCI Algorithms and Technologies: A Review},
  year   = {2026},
  note   = {Preprint submitted to IEEE Access}
}
```

## Manuscript and Reuse Notice

The paper is shared here for scholarly access and citation. The manuscript, its figures, and other included materials remain subject to the applicable author and/or publisher rights. **Do not assume that a software license such as MIT automatically applies to the paper PDF.** Any redistribution should comply with the applicable permissions and publication terms.

---

**Maintained by:** [Mohammad Hossein Koohi Ghamsari](https://github.com/mhkghamsari)
