# Magic Gamma-Ray Classification

## Overview

This project is a classification task that distinguishes between **gamma-ray** and **hadron** events detected by the MAGIC telescope. The dataset is preprocessed and analyzed using multiple machine learning models, including:

- K-Nearest Neighbors (KNN)
- Naive Bayes
- Logistic Regression
- Support Vector Machines (SVM)
- Deep Learning with TensorFlow

## Dataset

The dataset used is `magic04.data`, which consists of 10 features plus a target class (`g` for gamma rays and `h` for hadrons). The features include:

- fLength
- fWidth
- fSize
- fConc
- fConc1
- fAsym
- fM3Long
- fM3Trans
- fAlpha
- fDist

The target class is encoded as:

- `1` for gamma rays (`g`)
- `0` for hadrons (`h`)

## Requirements

The necessary Python packages are listed in `requirements.txt`:

```
numpy
pandas
matplotlib
scikit-learn
imbalanced-learn
tensorflow
```

## Installation

To run this project, install the required dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

### Running the Jupyter Notebook

The complete analysis is available in the Jupyter notebook:

```bash
jupyter notebook notebooks/magic_classification.ipynb
```

## Results

The best-performing model in this project is:

- **Support Vector Machine (SVM)** with an accuracy of **87%**.
- Deep learning models were trained with different hyperparameters to optimize performance.

## License

This project is open-source under the **MIT License**.

## Code of Conduct

We pledge to be inclusive, respectful, and welcoming to all contributors.

## Author

[Mayur Chandekar](https://github.com/your-github-username)




