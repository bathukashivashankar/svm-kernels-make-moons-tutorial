# svm-kernels-make-moons-tutorial
Tutorial notebook and report comparing linear, RBF, and polynomial SVM kernels on the non‑linear make_moons dataset with visual decision boundaries.

# Support Vector Machines with Different Kernels on the `make_moons` Dataset

This repository contains a self-contained tutorial that compares three Support Vector Machine (SVM) kernels — **linear**, **RBF**, and **polynomial** — on the non-linearly separable `make_moons` dataset. The goal is to give an intuitive understanding of the **kernel trick** by combining code, visual decision boundaries, and a short report. 

## Repository structure

- `svm_kernels_make_moons.ipynb`  
  Jupyter notebook with all code, plots, and explanatory markdown cells.

- `svm_kernels_report.pdf`  
  Short written tutorial/report exported from the notebook, suitable for course submission.

- `LICENSE`  
  Repository licence (e.g. MIT).
  
- `README.MD`  
  
## How to run the notebook

1. Clone this repository:

git clone https://github.com/bathukashivashankar/svm-kernels-make-moons-tutorial.git
cd svm-kernels-make-moons-tutorial

2. Create and activate a Python environment (optional but recommended).

3. Install dependencies:


Minimal requirements:

- `numpy`
- `matplotlib`
- `seaborn`
- `pandas`
- `scikit-learn` 

4. Launch Jupyter and open the notebook:

5. Run all cells from top to bottom to regenerate the plots and result table.

The code uses `sklearn.datasets.make_moons` to generate synthetic data, `sklearn.svm.SVC` for SVM classifiers, and meshgrid-based visualisations to show decision regions for each kernel. 

## What this tutorial covers

- Brief introduction to SVMs and the kernel trick (intuitive, with minimal math). 
- Why the `make_moons` dataset is a good example for non-linear classification.
- Training and evaluating SVMs with:
- Linear kernel
- RBF (Gaussian) kernel
- Degree-3 polynomial kernel
- Visual comparison of decision boundaries in 2D.
- Quantitative comparison of test accuracy across kernels.
- Discussion of when to use linear vs RBF vs polynomial kernels in practice. 

## Accessibility notes

Plots use a colorblind-friendly palette (`sns.set_palette("colorblind")`) and enlarged font sizes for better readability. In the PDF report, each figure includes descriptive alt-text so that screen-reader users can understand the visual content. 

## References

Key external resources used to prepare this tutorial include:

- scikit-learn User Guide: Support Vector Machines – https://scikit-learn.org/stable/modules/svm.html 
- scikit-learn documentation for `make_moons` – https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_moons.html 
- GeeksforGeeks, “Kernel Trick in Support Vector Classification” – https://www.geeksforgeeks.org/machine-learning/kernel-trick-in-support-vector-classification/   
- GeeksforGeeks, “How to Choose the Best Kernel Function for SVMs” – https://www.geeksforgeeks.org/machine-learning/how-to-choose-the-best-kernel-function-for-svms/  
- freeCodeCamp, “SVM Kernels Explained: How to Tackle Nonlinear Data in Machine Learning” – https://www.freecodecamp.org/news/svm-kernels-how-to-tackle-nonlinear-data-in-machine-learning/ 

