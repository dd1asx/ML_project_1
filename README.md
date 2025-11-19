# ML_project_1
Machine Learning Project that utilizes linear regression and random forest models to predict the log solubility of a molecule.

Molecular LogS Prediction

This is my first **machine learning** project.
It predicts the log solubility (LogS) of molecules using linear regression and random forest models.

**Dataset:**

I used the Delaney (ESOL) dataset, which contains:

SMILES strings

Experimental aqueous solubility (LogS)

Basic molecular descriptors

It’s one of the classic datasets for testing simple ML models in chemistry.

The dataset (Delaney/ESOL) was loaded directly from the YouTuber’s GitHub repository:

[https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv]

All credit for hosting the dataset goes to the original creator/uploader.

**What I Did:**

*Loaded a molecule dataset*

*Cleaned the data*

*Built two models from scikit-learn:*

1. Linear Regression

2. Random Forest Regressor

*Compared their performance using standard metrics*

*Plotted predictions vs. actual values*

Everything is inside the Jupyter notebook.

**Tools Used**

1. Google Colab

2. Python

3. Pandas, NumPy

4. Scikit-learn

5. Matplotlib / Seaborn

**Why did I choose these Models?**

Linear Regression → dead simple baseline

Random Forest → more flexible, handles non-linear relationships better

Using both gives a quick sense of what works and what doesn’t.

**How to Run**

Download or open the notebook and run it in **Colab**.

No complicated setup.
