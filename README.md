# ATLAS-GO-Dynamics: Systematic Ablation Study for GO Term Prediction

This repository contains the complete PyTorch implementation, data preprocessing pipelines, and ablation frameworks for our systematic study evaluating Protein Language Models (PLMs) against Molecular Dynamics features.

## 🔬 Core Architecture
* **Models Evaluated**: ESM2, ProtBERT, and custom TransformerGO configurations.
* **Feature Extraction**: ATLAS Molecular Dynamics (RMSF, Radius of Gyration) vs. Static Sequence Embeddings.
* **Explainable AI (XAI)**: Integrated Gradients attribution mapping.

## 📊 Dataset & Scope
* 1,289 Proteins
* 495 Multi-Label Gene Ontology (GO) terms
* 27 Distinct Deep Learning configurations tested
