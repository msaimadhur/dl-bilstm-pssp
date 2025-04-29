# Protein Secondary Structure Prediction using BiLSTM

This repository contains a deep learning project for **predicting protein secondary structures** using a **Bidirectional LSTM (BiLSTM)** model.

The work includes both:
- A **Jupyter Notebook** with full model implementation and experiments
- A **research paper** detailing the methodology, experiments, and results

---

## Contents

- [`proteinsecstruct.ipynb`](proteinsecstruct.ipynb) — Jupyter notebook implementing the BiLSTM model for secondary structure prediction
- [`Leveraging_Deep_Learning_Methodologies_for_Protein_Secondary_Structure_Prediction (2).pdf`](Leveraging_Deep_Learning_Methodologies_for_Protein_Secondary_Structure_Prediction%20(2).pdf) — Final project paper

---

## Project Overview

Protein secondary structure refers to local folded structures (such as **alpha-helices**, **beta-sheets**, and **coils**) within a protein sequence.  
Predicting these structures from the amino acid sequence is crucial for understanding protein functionality.

In this project:
- A **deep learning model** based on **Bidirectional LSTM** layers is developed.
- The task is formulated as a **three-class classification**: Helix (H), Sheet (E), and Coil (C).
- The model is trained and evaluated on benchmark protein datasets.

The full methodology, hyperparameters, training strategies, and evaluation results are discussed in the accompanying paper.

---

## Requirements

Install required packages using:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
