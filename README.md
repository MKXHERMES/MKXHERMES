# Jwaling Mehta

**Machine Learning Engineer | Multimodal AI · Mechanistic Interpretability · ML Systems**

I build and study machine learning systems from two directions: making models useful in real applications, and understanding what happens inside them.

My current research focus is **mechanistic interpretability of foundation models**, especially sparse representations, causal interventions, multimodal information flow, and cross-model feature structure.

## Current Focus

- Mechanistic interpretability of LLMs and vision-language models
- Sparse Autoencoders and representation learning
- Multimodal foundation models
- Efficient model fine-tuning and inference
- Reproducible ML experimentation
- Production-oriented ML systems

## Featured Work

### Universal Sparse Autoencoders — Reproduction

From-scratch reproduction of **Universal Sparse Autoencoders (ICML 2025)** across SigLIP, DINOv2, and ViT.

The project tests whether a shared sparse dictionary can learn concepts that transfer across independently trained vision backbones. It includes controlled baselines, cross-reconstruction analysis, qualitative feature inspection, reproducible experiment configs, and documented deviations from the original work.

**Repository:** [usae-repro](https://github.com/MKXHERMES/usae-repro)

---

### LoRA vs QLoRA vs DoRA

Controlled comparison of three parameter-efficient fine-tuning methods on Phi-3 Mini using identical data order, training budgets, and evaluation protocols.

The project measures generation quality, GPU memory usage, training cost, and statistical significance rather than comparing single headline metrics.

**Repository:** [peft-compare](https://github.com/MKXHERMES/peft-compare)

---

### CalmSpace

Full-stack ML application combining a React frontend, Node/Express backend, MongoDB, FastAPI, PyTorch, and a fine-tuned transformer model for emotion analysis and mood tracking.

**Repository:** [CalmSpace](https://github.com/MKXHERMES/CalmSpace)

## Research

I am currently working on **Neural Trace Auditor**, a mechanistic-interpretability framework for studying how visual evidence propagates through multimodal language models.

The project investigates:

- visual-token interventions
- sparse-autoencoder features
- activation and logit analysis
- causal feature ablation
- cross-model representation correspondence
- hallucination and grounding mechanisms

The research repository is currently private while the associated work is under review.

## Tools I Work With

**ML / Research**

`Python` · `PyTorch` · `Transformers` · `NumPy` · `scikit-learn` · `Hugging Face`

**ML Systems**

`FastAPI` · `Docker` · `Linux` · `CUDA` · `Weights & Biases`

**Application Development**

`React` · `Node.js` · `Express` · `MongoDB`

**Cloud / Compute**

`AWS` · `GCP` · GPU cloud infrastructure

## What I Care About

I am particularly interested in questions like:

> What representations does a neural network learn?

> Which internal components causally produce a model's behaviour?

> Do learned features transfer between different model families?

> Can interpretability move from visualization to actual model debugging and intervention?

My long-term goal is to work at the intersection of **machine learning engineering and model-level research**.
