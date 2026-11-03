# ANN2DL-2025

Group projects developed for the **Artificial Neural Networks and Deep Learning** course at Politecnico di Milano, academic year 2025.

The repository collects two homework assignments, each kept in its own folder.

Group members: Alongi Tommaso, Carugati Federico, Paolini Francesco, Romani Alessandro

---

## Projects

### `ineuralini_notebooks` — Time Series Classification

An LSTM-based approach to a multivariate time series classification problem, covering sequence preprocessing, recurrent architecture design and evaluation.

### `P.E.K.K.A.tori_notebooks` — Breast Cancer Subtype Classification on WSIs

Deep learning pipelines for the classification of breast cancer molecular subtypes from Whole Slide Images (WSIs).

**Main contributions**

- **Patch-based inference** — WSIs are tiled into patches, classified independently, and aggregated into a slide-level prediction.
- **Masking strategies** — tissue/background segmentation to discard uninformative regions and reduce noise during both training and inference.
- **Hierarchical inference** — a two-stage scheme in which a specialized model refines predictions on the hardest subtypes (Luminal A / Luminal B).
- **Dataset cleaning** — cosine similarity between feature embeddings used to identify near-duplicate and mislabelled patches.
- **Ensemble learning** — predictions from several backbones combined to improve robustness over any single model.


## Repository structure

```
ANN2DL-2025/
├── ineuralini_report_first_challenge_ANN2DL/          # Homework 1 REPORT— LSTM time series classification
├── P.E.K.K.A.tori_report_first_challenge_ANN2DL/          # Homework 2 REPORT— WSI breast cancer subtyping
├── ineuralini_notebooks/          # Homework 1 — LSTM time series classification
└── P.E.K.K.A.tori_notebooks/      # Homework 2 — WSI breast cancer subtyping

```

-
