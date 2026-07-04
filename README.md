# Project Notebooks — ML(Machine Learning)

This document describes every `.ipynb` notebook in the project folder, organized in a logical learning sequence — from basic Python, through NumPy/Pandas/Matplotlib fundamentals, to machine learning with scikit-learn.

## Data files used across notebooks
- **Iris_dataset.csv** — The classic Iris flower dataset (sepal/petal length & width, species). Used by `DecisionTree.ipynb` and referenced by `iris_dataset.ipynb`.
- **sales.csv** — Sales records data.
- **data2.xlsx** — Excel dataset loaded and explored in `SKlearn.ipynb`.

---

## Notebooks

### 1. Python Basics

#### 1.ipynb – 4.ipynb (Lab Exercise 1)
These four notebooks together make up **Lab Exercise 1**, a set of beginner Python exercises built around tuples:

- **1.ipynb** — Takes 10 numbers from user input, stores them in a tuple, and manually finds the minimum and maximum values by looping through the tuple.
- **2.ipynb** — Similar to `1.ipynb`, but the number of inputs is user-defined (`n`). Counts and prints values that are greater than the average of the entered numbers.
- **3.ipynb** — Takes exactly 3 numbers as input, stores them in a tuple, and unpacks/prints them individually (`a, b, c = t`).
- **4.ipynb** — Takes `n` numbers as input, builds a tuple, then asks the user to pick two index positions and swaps/compares values based on a chosen criterion.

#### Test.ipynb
A short scratch/test notebook: prints a welcome message, performs simple variable arithmetic, an if-elif-else comparison example, and a min/max-finding loop exercise similar to `1.ipynb`.

### 2. NumPy

#### assisment1.ipynb
NumPy indexing exercise: creates an 11×11 array with `np.arange(1,122).reshape(11,11)` and demonstrates fancy indexing (extracting an anti-diagonal using paired row/column index lists).

#### LabExercise-2.ipynb
A NumPy lab exercise sheet with 10 markdown-labeled tasks: creating null/range vectors, a 3x3x3 random array, and other array-construction/manipulation exercises.

#### demo.ipynb / numpy.ipynb
(Identical content) A structured walkthrough of NumPy fundamentals: creating arrays, checking data types, array attributes, indexing/slicing, reshaping, mathematical operations, and other core NumPy operations, organized under labeled markdown comment headers.

### 3. Pandas

#### pandas.ipynb
A series of Pandas exercises using a small custom dataset of student roll numbers and marks across multiple subjects. Covers DataFrame creation, indexing, and basic data manipulation (39 code cells, no markdown headers).

#### Exercise_3.ipynb
A structured set of ~17 Pandas practice questions (Q&A style with markdown headers) covering Series arithmetic, comparisons, DataFrame conversions, and other Pandas operations — a lab-style exercise sheet.

### 4. Matplotlib

#### MATPLOTLIB.ipynb
A demo/practice notebook for Matplotlib: scatter plots, line plots, and bar charts (e.g., comparing "sales of company A/B", marks vs. subjects), built with `matplotlib`, `numpy`, and `pandas`.

#### Exercise_4.ipynb
A structured set of Matplotlib practice questions (12 markdown-labeled tasks) covering line plots, axis labeling, multiple lines with legends, and other basic plotting techniques.

### 5. Machine Learning (scikit-learn)

#### iris_dataset.ipynb
Loads the Iris dataset directly via `sklearn.datasets.load_iris()`, then explores and visualizes relationships between sepal length/width and petal length/width using labeled variables and plots.

#### SKlearn.ipynb
A large scikit-learn practice notebook. Loads `data2.xlsx` with pandas, then explores it using `plotly.express`, `matplotlib`, `seaborn`, `scipy.stats`, and evaluates models using `sklearn.metrics` (e.g., `r2_score`). Covers general data analysis and regression/statistics workflow (30 code cells, no markdown headers).

#### DecisionTree.ipynb
Loads the Iris dataset (from CSV via `sklearn.datasets` and `pandas`), performs data visualization (title: "Data Visualization"), and builds a **Decision Tree classifier** using `sklearn.model_selection.train_test_split` and related scikit-learn tools.

#### RandomForest.ipynb
Currently an empty notebook (single blank code cell) — likely intended as a follow-up to `DecisionTree.ipynb` for building a Random Forest model, but not yet started.

#### MNIST.ipynb
A machine learning notebook using the **MNIST handwritten digits dataset** (fetched via `sklearn.datasets.fetch_openml`). Covers exploring the dataset, building a **binary classifier**, and evaluating it with a **confusion matrix** and other classification metrics.

---

## Summary Table

| # | Notebook | Topic |
|---|---|---|---|
| 1 | 1.ipynb – 4.ipynb | Lab Exercise 1 — Python basics (tuples, loops, input handling) |
| 2 | Test.ipynb | Misc scratch/test code |
| 3 | assisment1.ipynb | NumPy indexing |
| 4 | LabExercise-2.ipynb | NumPy lab exercises |
| 5 | demo.ipynb / numpy.ipynb | NumPy fundamentals |
| 6 | pandas.ipynb | Pandas basics |
| 7 | Exercise_3.ipynb | Pandas exercise sheet |
| 8 | MATPLOTLIB.ipynb | Matplotlib demo |
| 9 | Exercise_4.ipynb | Matplotlib exercise sheet |
| 10 | iris_dataset.ipynb | Iris dataset exploration |
| 11 | SKlearn.ipynb | scikit-learn / regression workflow |
| 12 | DecisionTree.ipynb | Iris + Decision Tree classifier |
| 13 | RandomForest.ipynb | Random Forest |
| 14 | MNIST.ipynb | MNIST binary classifier |
