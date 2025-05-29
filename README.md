# Operation-aware Neural Networks for User Response Prediction

A complete implementation and analysis of the paper **“Operation-aware Neural Networks for User Response Prediction”** (arXiv:1904.12579), developed at FAST-NU by Shaikh Azan Asim and Nabeel Uddin.

---

## Repository Structure

```
.
├── README.md                             # This file
├── paper/
│   └── 1904.12579v1_copy.pdf             # Original arXiv paper
├── report/
│   └── Operation-aware Neural Networks for User Response Prediction.docx
├── slides/
│   └── operation_aware_presentation.pptx
├── notebook/
│   └── recysy-project.ipynb              # Jupyter notebook for synthetic-data demo
├── synthetic_dataset.zip                 # (Optional) Synthetic data used in demo
└── code/
    ├── data_utils.py                     # Data loading and preprocessing
    ├── models.py                         # UNet, GAN stub, discrepancy net definitions
    └── train_segmentation.py             # Training script for segmentation
```

---

## Setup & Requirements

This project was developed on **Google Colab** with GPU support. To run locally:

1. **Clone the repository**

   ```bash
   git clone <repo-url>
   cd <repo-folder>
   ```

2. **(Optional) Create a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   pip install torch torchvision opencv-python scikit-image matplotlib tqdm Pillow
   ```

---

## Running the Notebook

1. Open `notebook/recysy-project.ipynb` in Jupyter or Colab.
2. If using synthetic data, unzip `synthetic_dataset.zip`:

   ```bash
   unzip synthetic_dataset.zip
   ```
3. Run all cells to:

   * Generate synthetic images & masks
   * Train a toy UNet segmentation model
   * (Stub) Visualize resynthesis & discrepancy outputs

---

## Report

Detailed critical review and implementation insights are in:

```
report/Operation-aware Neural Networks for User Response Prediction.docx
```

Sections include:

* Abstract, Introduction, Related Work
* ONN architecture breakdown (with figures)
* Experiments & results analysis
* “What We Learned” summary

---

## Presentation Slides

Download and view:

```
slides/operation_aware_presentation.pptx
```

Covers:

* Motivation & challenge
* ONN key idea & architecture (Figures 1–5)
* Experiment results (Tables 1–2, Figure 7)
* What we learned & future work

---

## Original Paper

```
paper/1904.12579v1_copy.pdf
```

Please cite as:

> Yang, Y., Xu, B., Shen, F., & Zhao, J. (2019). Operation-aware Neural Networks for User Response Prediction. *arXiv preprint arXiv:1904.12579*.

---

## License

This project is licensed under the **MIT License**. See `LICENSE` for details.

---

## Acknowledgments

* Original authors: Yi Yang, Baile Xu, Furao Shen, Jian Zhao
* Developed by Shaikh Azan Asim & Nabeel Uddin, FAST-NU
* Inspired by multi-sense embeddings and deep CTR models

---

*Feel free to open issues or pull requests!*
