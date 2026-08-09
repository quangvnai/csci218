# CSCI218: Foundations of Artificial Intelligence

Welcome to the laboratory repository for **CSCI218: Foundations of Artificial Intelligence**.


## ⚙️ Environment Setup

If Python/pip is not installed, install **Miniforge** (recommended) or **Anaconda**:

* 🍏 **macOS**: Install via Homebrew `brew install miniforge` or download from [Miniforge (conda-forge)](https://github.com/conda-forge/miniforge#miniforge3).
* 🪟 **Windows**: Download setup `.exe` from [Miniforge (conda-forge)](https://github.com/conda-forge/miniforge#miniforge3).

### Setup Environment
Open **Terminal** (macOS) or **Miniforge Prompt** (Windows):
```bash

# These commands are run only once
conda config --add channels conda-forge
conda config --set channel_priority strict
conda create -n csci218 python=3.10 jupyter -y

# At the start of each lab, run these commands:
conda activate csci218
jupyter notebook
```

<details>
<summary><b>📦 Anaconda Alternative (Click to expand)</b></summary>

Download installer from [anaconda.com/download](https://www.anaconda.com/download). Then open **Anaconda Prompt** / **Terminal**:
```bash
conda config --add channels conda-forge
conda config --set channel_priority strict
conda create -n csci218 python=3.10 jupyter -y
conda activate csci218
```

</details>

---

## 📅 Lab Overview

<details>
<summary><b>📁 Week 3 — K-Nearest Neighbours (KNN) [Click to expand]</b></summary>

* **Slides**: Available in `Week3/slides/`
* **Lab Notebooks**:
  * `Week3/week3-task1.ipynb`: Task 1 — Introduction to KNN (Iris Dataset)
  * `Week3/week3-task2.ipynb`: Task 2 — Image Classification using KNN & Color Histograms
* **Dataset Setup (Action Required)**:
  1. Go to **Moodle** -> **Week 3 Lab**.
  2. Download `flowers.zip`.
  3. Unzip `flowers.zip` directly inside the `Week3/` directory (resulting in `Week3/flowers/`).

</details>
