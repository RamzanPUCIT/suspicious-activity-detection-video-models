# Suspicious Activity Detection using VideoMAE, SlowFast, and I3D

This repository contains my M.Phil Artificial Intelligence assignment work on **Suspicious Activity Detection** using three state-of-the-art video understanding models:

- VideoMAE
- SlowFast
- I3D

The project performs a **comparative analysis** of these models on a real-world suspicious and harmful content classification task.

---

## Project Overview

The goal of this project is to classify video clips into the following 4 classes:

- Adult Content
- Harmful Content
- Safe
- Suicide

The work includes:

- end-to-end dataset preparation
- model training and validation
- checkpoint saving
- best-model saving
- test evaluation
- performance graph generation
- final results recording for comparison

---

## Dataset

Dataset used in this project:

- **Kaggle Dataset:** `aryansraut/preprocessed-ucf-crime-dataset-visual`

Final extracted dataset folder used in Colab:

- `/content/TikHarm_frames_16`

Dataset split structure:

- train
- val
- test

Each sample contains:

- **16 RGB frames**
- frame size: **224 x 224**

Classes:

- Adult Content
- Harmful Content
- Safe
- Suicide

---

## Models Used

### 1. VideoMAE
VideoMAE is a transformer-based video understanding model that learns spatiotemporal representations from video frames.

### 2. SlowFast
SlowFast is a dual-pathway video model that captures both slow semantic information and fast motion information.

### 3. I3D
I3D (Inflated 3D ConvNet) is a deep video classification model that extends 2D convolutions into 3D convolutions to learn both spatial and temporal features from consecutive video frames.

---

## Workflow

The implementation includes the following steps:

1. Dataset download from Kaggle
2. Dataset extraction and verification
3. Data loading for train, validation, and test sets
4. Model loading and configuration
5. Training and validation
6. Checkpoint saving for resume support
7. Best model saving
8. Test evaluation
9. Graph generation
10. Final result saving for comparison

---

## Project Structure

```bash
suspicious-activity-detection-video-models/
│
├── VideoMAE/
│   ├── notebook/
│   ├── plots/
│   ├── results/
│
├── SlowFast/
│   ├── notebook/
│   ├── plots/
│   ├── results/
│
├── I3D/
│   ├── notebook/
│   ├── plots/
│   ├── results/
│
├── images/
├── README.md
└── requirements.txt

Author

Muhammad Ramzan
M.Phil Artificial Intelligence
PUCIT, University of the Punjab
