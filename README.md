# Suspicious Activity Detection using Video Models 🎥🛡️

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.12-blue)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)]()

---

## 🔹 Project Summary

This project compares **three state-of-the-art video understanding models** — VideoMAE, SlowFast, and I3D — to detect **suspicious or harmful content** in videos.
It is designed for students, researchers, and AI enthusiasts to understand **video classification workflows** and evaluate modern video models on real-world datasets.

---

## 🔹 Key Features

* Classifies video clips into **4 categories**:

  * Adult Content
  * Harmful Content
  * Safe
  * Suicide
* Uses three advanced video models for comparison:

  * **VideoMAE** – Transformer-based video understanding model
  * **SlowFast** – Dual-pathway video model for semantic + motion capture
  * **I3D** – 3D ConvNet for spatial and temporal video features
* End-to-end workflow:

  * Dataset preparation
  * Model training and validation
  * Saving best models and checkpoints
  * Test evaluation and performance visualization
* Ready-to-run **Jupyter notebooks** for each model

---

## 🔹 Dataset

**Dataset used:** [preprocessed UCF-Crime Dataset](https://www.kaggle.com/aryansraut/preprocessed-ucf-crime-dataset-visual)

**Structure:**

```
/TikHarm_frames_16/
│── train/
│── val/
│── test/
```

* Each sample contains **16 RGB frames** (224x224)
* Classes: Adult Content, Harmful Content, Safe, Suicide

---

## 🔹 Models Implemented

| Model        | Description                                                        |
| ------------ | ------------------------------------------------------------------ |
| **VideoMAE** | Transformer-based model learning spatiotemporal representations    |
| **SlowFast** | Dual-pathway model capturing slow semantic info + fast motion info |
| **I3D**      | Inflated 3D ConvNet for spatiotemporal feature extraction          |

---

## 🔹 Workflow

1. **Dataset download** from Kaggle
2. **Dataset extraction & verification**
3. **Data loading** (train, validation, test sets)
4. **Model loading & configuration**
5. **Training & validation**
6. **Checkpoint saving** for resume support
7. **Best model saving**
8. **Test evaluation**
9. **Graph generation** for performance comparison
10. **Final result recording**

---

## 🔹 Quick Start

1. **Clone the repository**

```bash
git clone https://github.com/RamzanPUCIT/suspicious-activity-detection-video-models.git
cd suspicious-activity-detection-video-models
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Open Jupyter notebooks**

```bash
jupyter notebook VideoMAE/notebook/YourNotebook.ipynb
```

4. **Follow notebooks** for training, testing, evaluation, and results visualization

---

## 🔹 Project Structure

```
suspicious-activity-detection-video-models/
│
├── VideoMAE/
│   ├── notebook/
│   ├── plots/
│   └── results/
├── SlowFast/
│   ├── notebook/
│   ├── plots/
│   └── results/
├── I3D/
│   ├── notebook/
│   ├── plots/
│   └── results/
├── images/
├── README.md
└── requirements.txt
```

---

## 🔹 Contributing

Contributions are **welcome**! You can help by:

* Improving README clarity or formatting
* Adding usage examples or screenshots
* Documenting model results or analysis

**How to contribute:**

1. Fork the repository
2. Make your edits (README, examples, docs)
3. Submit a Pull Request (PR)
4. Mention this issue/PR in your description

---

## 🔹 Author

**Muhammad Ramzan**
M.Phil Artificial Intelligence, PUCIT, University of the Punjab

---

## 🔹 License

This project is licensed under the [MIT License](LICENSE).

---

