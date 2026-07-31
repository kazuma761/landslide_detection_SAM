🌍 Landslide Detection using Hybrid SAM + Swin Transformer

A this one segmentation-assisted transformer framework for landslide detection in remote sensing imagery.

📌 Overview

Accurate landslide detection from satellite imagery is critical for disaster risk management and hazard mitigation. Traditional CNN-based methods capture local features but struggle with global context, while transformer-based models improve contextual modeling but often lack precise boundary localization.

This project proposes a Segmentation-Guided Swin Transformer Framework, integrating:

Segment Anything Model (SAM) for region-level segmentation

Swin Transformer for hierarchical contextual classification

The goal is to enhance spatial focus, improve boundary delineation, and increase detection robustness.

🧠 Methodology
Workflow
Remote Sensing Image
        ↓
Preprocessing
        ↓
SAM Segmentation
        ↓
Segmentation-Guided Feature Extraction
        ↓
Swin Transformer Classification
        ↓
Evaluation

Key Idea

Instead of using segmentation as a final output, segmentation masks are used as spatial priors to guide transformer-based feature learning.

📂 Dataset

Bijie Landslide Dataset

Remote sensing images with landslide annotations

Standard preprocessing and augmentation pipeline applied

📊 Evaluation Metrics

Segmentation Metrics

IoU (Intersection over Union)

Dice Coefficient

Classification Metrics

Accuracy

Precision

Recall

F1-Score

🚀 Current Progress

Literature review completed

Dataset prepared and preprocessed

SAM implemented for region-level segmentation

Preliminary segmentation analysis conducted

Hybrid framework architecture designed

🔮 Future Work

Integrate Swin Transformer backbone

Train and validate SAM + Swin framework

Comparative evaluation against standalone Swin model

Boundary-level performance analysis

🛠️ Tech Stack

Python

PyTorch

OpenCV

Segment Anything Model (SAM)

Swin Transformer
