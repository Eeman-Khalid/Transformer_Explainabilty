# Transformer Explainability Project

## Objective
Train a Transformer-based sentiment classifier and analyze predictions using attention, SHAP, and LIME.

## Dataset
Amazon Polarity Dataset (HuggingFace)

## Model
DistilBERT (fine-tuned for binary sentiment classification)

## Features
- Attention visualization (heatmaps)
- SHAP explanations (20 samples)
- LIME explanations (20 samples)

## Outputs
Saved in /outputs folder:
- attention_heatmap.png
- shap_values.pkl
- lime_explanation.html

## How to run
1. Install requirements
2. Open notebook.ipynb
3. Run all cells sequentially