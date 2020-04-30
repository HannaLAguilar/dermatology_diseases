# Dermatology diseases classification

In this project, the principal component analysis algorithm (PCA), cross-validation and machine learning classification algorithms were used to classify the input data into 6 different dermatological pathologies. The model reached an accuracy of 97% with SVM.

### Technologies used:

- Python
- pandas, numpy
- PCA analysis, cross-validation
- sklearn, scipy
- classification algorithms: K-Nearest neighbours (KNN), suport vector machine (SVM), decision tree, gaussian baive bayes
- matplotlib, seaborn
- jupyter notebooks, anaconda

## Data
Each line corresponds to a patient and contains 34 attributes and their class (the last value of each sample). Some samples include invalid values represented by the '?'. The complete description of this dataset can be found at: https://archive.ics.uci.edu/ml/datasets/Dermatology

## Installation

Using [Anaconda](https://www.anaconda.com/products/individual), in an enviroment with python 3, install the following packages:
```
conda install jupyter, numpy, pandas=0.25, matplotlib, seaborn
conda install -c anaconda scikit-learn

```




