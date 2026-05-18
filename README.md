<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">

# MATH4230-FINAL-PROJECT

<em>Empowering Innovation Through Data-Driven Excellence</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/ChristianRodriguez46/Math4230-Final-Project?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/ChristianRodriguez46/Math4230-Final-Project?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/ChristianRodriguez46/Math4230-Final-Project?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>


</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Project Structure](#project-structure)
  - [Project Index](#project-index)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
- [Python Environment](#python-environment)
- [Required Python Libraries](#required-python-libraries)
- [Setup Instructions for Linux / macOS](#setup-instructions-for-linux--macos)
- [Setup Instructions for Windows](#setup-instructions-for-windows)
- [Setup Instructions for WSL](#setup-instructions-for-wsl)
- [Running the Project](#running-the-project)
- [Important Runtime Notes](#important-runtime-notes)
- [Notes About Large Files](#notes-about-large-files)
- [Reproducibility](#reproducibility)
- [Testing and Validation](#testing-and-validation)

---

## Overview

Math4230-Final-Project is a versatile developer toolkit designed to facilitate the development, analysis, and visualization of machine learning models. It combines educational notebooks with practical tools to support robust, interpretable, and scalable data science workflows. Whether you're exploring data, building predictive models, or validating results, this project provides a solid foundation for advanced ML development.

**Why Math4230-Final-Project?**

This project aims to streamline your machine learning journey with core features including:

- **Modular Notebooks:** Covering techniques from linear regression to neural networks, supporting both learning and deployment.
- **Data Profiling & Validation:** Tools for dataset analysis and model evaluation to ensure reliability.
- **Interpretability Focus:** Emphasizes transparent models like decision trees and regularization methods.
- **Open-Source Collaboration:** Encourages community contributions and customization for diverse use cases.
- **Educational & Practical:** Bridges theoretical concepts with real-world applications for developers and data scientists alike.

---


## Dataset

The dataset used for the final project is:

**Student Lifestyle, Mental Health and Burnout Insight**

Dataset link:

https://www.kaggle.com/datasets/ayeshasiddiqa123/student-health

Important note:

The dataset file is **not included in this GitHub repository** because it is too large for GitHub. To run the notebooks, you must manually download the dataset from Kaggle and place it inside the `Datasets/` folder.

After downloading the dataset from Kaggle, place the CSV file here:

```text
Math4230-Final-Project/
└── Datasets/
    └── student_mental_health_burnout_1M.csv
```

If the downloaded file has a different name, either rename it to:

```text
student_mental_health_burnout_1M.csv
```

or update the file path in the Chapter 2 notebook.

There may be another dataset file in the repository because I originally considered more than one dataset option. The final report uses the Kaggle student-health dataset linked above.

---

## Features

| Component | Details |
| :--- | :--- |
| **Notebook-Based Analysis** | The project is organized around Jupyter notebooks for each major statistical learning method covered in MATH 4230. |
| **Dataset Preparation** | Chapter 2 handles dataset inspection, train/validation/test splitting, dummy encoding, scaling, and saved reusable arrays for later chapters. |
| **Regression Modeling** | Includes simple linear regression, multiple linear regression, Ridge regression, Lasso regression, tree regression, ensemble regression, and neural network regression. |
| **Classification Modeling** | Includes logistic regression, classification trees, random forest classification, gradient boosting classification, support vector machines, and K-nearest neighbors. |
| **Model Validation** | Uses train/test evaluation, cross-validation, bootstrap resampling, out-of-bag error, and diagnostic plots to check model stability and performance. |
| **Interpretability Focus** | Emphasizes coefficients, odds ratios, feature importance, decision rules, subset selection, and PCA loadings so model results can be explained clearly. |
| **Saved Outputs** | Figures are saved by chapter in the `figures/` folder, and model results are saved in the `results/` folder for reuse in later chapters. |
| **Manual Dataset Setup** | The main Kaggle dataset must be downloaded manually and placed in the `Datasets/` folder because the file is too large for GitHub. |
| **Reproducibility** | The notebooks use `RANDOM_STATE = 230` where possible to make splits, samples, tuning, and plots more consistent across runs. |
| **Project Documentation** | Includes notebook markdown explanations, PDF outputs, final report sections, and this README for setup and usage instructions. |
---

## Project Structure

```sh
└── Math4230-Final-Project/
    ├── Datasets
    │   ├── Dataset - short descriptions.txt
    │   └── Gaming_Academic_Performance.csv
    ├── LICENSE
    ├── figures
    │   ├── ch02
    │   ├── ch03
    │   ├── ch04
    │   ├── ch05
    │   ├── ch06
    │   ├── ch07
    │   ├── ch08
    │   ├── ch09
    │   ├── ch10
    │   ├── ch11
    │   ├── ch12
    │   └── ch13
    ├── notebooks
    │   ├── Ch02_Dataset_Profile.ipynb
    │   ├── Ch03_Simple_Linear_Regression.ipynb
    │   ├── Ch04_Multiple_Linear_Regression.ipynb
    │   ├── Ch05_Logistic_Regression.ipynb
    │   ├── Ch06_Resampling_CV_Bootstrap.ipynb
    │   ├── Ch07_Regularization_Ridge_Lasso.ipynb
    │   ├── Ch08_Decision_Trees.ipynb
    │   ├── Ch13_Neural_Networks.ipynb
    │   ├── ch09_tree_ensembles.ipynb
    │   ├── ch10_support_vector_machines.ipynb
    │   ├── ch11_k_nearest_neighbors.ipynb
    │   └── ch12_principal_component_analysis.ipynb
    ├── pdf
    │   ├── Ch03_Simple_Linear_Regression.pdf
    │   ├── Ch04_Multiple_Linear_Regression.pdf
    │   ├── Ch05_Logistic_Regression.pdf
    │   ├── Ch06_Resampling_CV_Bootstrap.pdf
    │   ├── Ch07_Regularization_Ridge_Lasso.pdf
    │   ├── Ch08_Decision_Trees.pdf
    │   ├── Ch13_Neural_Networks.pdf
    │   ├── ch09_tree_ensembles.pdf
    │   ├── ch10_support_vector_machines.pdf
    │   ├── ch11_k_nearest_neighbors.pdf
    │   ├── ch12_principal_component_analysis.pdf
    │   └── updates
    └── results
        ├── X_test.npy
        ├── X_train.npy
        ├── X_val.npy
        ├── ch02
        ├── ch03
        ├── ch04
        ├── ch05
        ├── ch06
        ├── ch07
        ├── ch08
        ├── ch09
        ├── ch10
        ├── ch11
        ├── ch12
        ├── ch13
        ├── df_test.csv
        ├── df_train.csv
        ├── df_val.csv
        ├── feature_names.pkl
        ├── standard_scaler.pkl
        ├── y_test_cls.npy
        ├── y_test_reg.npy
        ├── y_train_cls.npy
        ├── y_train_reg.npy
        ├── y_val_cls.npy
        └── y_val_reg.npy
```

---

### Project Index

<details open>
	<summary><b><code>MATH4230-FINAL-PROJECT/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/LICENSE'>LICENSE</a></b></td>
					<td style='padding: 8px;'>- Provides the foundational licensing framework that governs the entire project, ensuring legal clarity and open-source accessibility<br>- It establishes permissions for use, modification, and distribution, supporting the projects goal of fostering collaborative development and broad adoption within the software ecosystem.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- notebooks Submodule -->
	<details>
		<summary><b>notebooks</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ notebooks</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/Ch04_Multiple_Linear_Regression.ipynb'>Ch04_Multiple_Linear_Regression.ipynb</a></b></td>
					<td style='padding: 8px;'>- Summary of <code>notebooks/Ch04_Multiple_Linear_Regression.ipynb</code>This notebook demonstrates the application of multiple linear regression techniques to analyze and model relationships between multiple features and a target variable<br>- It serves as an educational example within the broader project, illustrating key concepts such as feature selection, model fitting, and evaluation<br>- By providing practical insights into how multiple predictors influence the outcome, this notebook supports the projects goal of building robust, interpretable predictive models as part of its overall data analysis and machine learning architecture.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/ch12_principal_component_analysis.ipynb'>ch12_principal_component_analysis.ipynb</a></b></td>
					<td style='padding: 8px;'>- Principal Component Analysis NotebookThis notebook demonstrates the application of Principal Component Analysis (PCA) within the project<br>- It serves as an educational and analytical resource for understanding how PCA can be used to reduce dimensionality, visualize high-dimensional data, and extract meaningful features<br>- By integrating this analysis, the project enhances its capability to preprocess and interpret complex datasets, supporting downstream tasks such as modeling and insights generation across the overall architecture.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/Ch08_Decision_Trees.ipynb'>Ch08_Decision_Trees.ipynb</a></b></td>
					<td style='padding: 8px;'>- Decision Trees Analysis NotebookThis notebook serves as a comprehensive exploration of decision tree algorithms within the broader machine learning project<br>- It demonstrates how decision trees are used for classification and regression tasks, illustrating their application in real-world scenarios<br>- The notebook integrates seamlessly into the overall architecture by providing insights into model training, evaluation, and interpretability, thereby supporting the projects goal of building transparent and effective predictive models.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/ch11_k_nearest_neighbors.ipynb'>ch11_k_nearest_neighbors.ipynb</a></b></td>
					<td style='padding: 8px;'>- The <code>notebooks/ch11_k_nearest_neighbors.ipynb</code> file serves as an instructional guide within the project, demonstrating how to implement and utilize the k-Nearest Neighbors (k-NN) algorithm for classification tasks<br>- It provides practical examples and insights into applying this algorithm to real-world data, illustrating its role within the broader machine learning workflow<br>- This notebook complements the overall architecture by offering a hands-on approach to understanding and deploying k-NN, which can be integrated into larger data analysis and predictive modeling pipelines across the project.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/Ch06_Resampling_CV_Bootstrap.ipynb'>Ch06_Resampling_CV_Bootstrap.ipynb</a></b></td>
					<td style='padding: 8px;'>- Summary: This notebook demonstrates the application of resampling techniques, including cross-validation and bootstrap methods, to evaluate and improve model performance<br>- It serves as a practical guide within the broader project architecture to ensure robust model validation, helping to prevent overfitting and assess the generalization capability of machine learning models across different datasets and scenarios<br>- This aligns with the projects goal of building reliable, well-validated predictive models within the overall data science workflow.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/Ch02_Dataset_Profile.ipynb'>Ch02_Dataset_Profile.ipynb</a></b></td>
					<td style='padding: 8px;'>- The <code>notebooks/Ch02_Dataset_Profile.ipynb</code> notebook serves as an exploratory data analysis tool within the project<br>- Its primary purpose is to generate comprehensive profiles of datasets, enabling users to understand data distributions, identify potential issues, and gain insights essential for effective model development<br>- This step is crucial in the broader architecture, as it informs data preprocessing, feature engineering, and model selection processes, ensuring the foundation for subsequent stages is well-understood and optimized.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/Ch13_Neural_Networks.ipynb'>Ch13_Neural_Networks.ipynb</a></b></td>
					<td style='padding: 8px;'>- SummaryThis notebook serves as a comprehensive guide to building and training neural networks within the project<br>- It demonstrates how to implement deep learning models to solve complex problems, integrating key concepts such as model architecture, optimization, and evaluation<br>- Positioned within the broader codebase, this file provides foundational insights and practical examples that support the development of scalable, high-performance neural network solutions across the project’s architecture.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/Ch07_Regularization_Ridge_Lasso.ipynb'>Ch07_Regularization_Ridge_Lasso.ipynb</a></b></td>
					<td style='padding: 8px;'>- Summary: This Jupyter notebook serves as an instructional guide within the project, demonstrating how regularization techniques—specifically Ridge and Lasso regression—are applied to improve model performance and prevent overfitting<br>- It fits into the broader architecture by illustrating key concepts of model regularization, complementing other modules focused on data preprocessing, feature engineering, and model evaluation<br>- Overall, this notebook enhances the understanding of regularization methods as essential tools for building robust, generalizable machine learning models within the project.---</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/Ch03_Simple_Linear_Regression.ipynb'>Ch03_Simple_Linear_Regression.ipynb</a></b></td>
					<td style='padding: 8px;'>- Simple Linear Regression NotebookThis notebook demonstrates the fundamental process of building and evaluating a simple linear regression model<br>- It serves as an educational example within the broader project architecture, illustrating how to model the relationship between a single feature and a target variable<br>- The insights gained here lay the groundwork for more complex modeling tasks across the project, emphasizing core concepts of data analysis, model training, and performance assessment in a clear and accessible manner.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/Ch05_Logistic_Regression.ipynb'>Ch05_Logistic_Regression.ipynb</a></b></td>
					<td style='padding: 8px;'>- Summary of <code>notebooks/Ch05_Logistic_Regression.ipynb</code>This notebook serves as a comprehensive guide to implementing and understanding logistic regression within the broader machine learning project<br>- It demonstrates how to apply logistic regression techniques to classify data effectively, illustrating key concepts such as model training, evaluation, and interpretation<br>- As part of the overall architecture, this notebook provides foundational insights into binary classification tasks, supporting the projects goal of building robust predictive models and facilitating data-driven decision-making.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/ch09_tree_ensembles.ipynb'>ch09_tree_ensembles.ipynb</a></b></td>
					<td style='padding: 8px;'>- The <code>notebooks/ch09_tree_ensembles.ipynb</code> file serves as an instructional notebook that explores the application of tree ensemble methods within the broader machine learning framework of the project<br>- It demonstrates how combining multiple decision trees enhances predictive performance and robustness, aligning with the chapters focus on advanced ensemble techniques<br>- This notebook provides practical insights and examples that integrate into the overall architecture by illustrating key concepts and methodologies used for building scalable, accurate models in the project’s machine learning pipeline.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/notebooks/ch10_support_vector_machines.ipynb'>ch10_support_vector_machines.ipynb</a></b></td>
					<td style='padding: 8px;'>Certainly! Please provide the content of the code file or specify the code youd like summarized, and Ill craft a succinct overview highlighting its purpose within the overall project architecture.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- Datasets Submodule -->
	<details>
		<summary><b>Datasets</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ Datasets</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/Datasets/Dataset - short descriptions.txt'>Dataset - short descriptions.txt</a></b></td>
					<td style='padding: 8px;'>- Provides an overview of student performance and well-being by integrating datasets on gaming habits, academic outcomes, mental health, and lifestyle factors<br>- Facilitates predictive modeling, behavioral analysis, and data visualization to understand how various personal and environmental influences impact student success and mental health in educational settings.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- pdf Submodule -->
	<details>
		<summary><b>pdf</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ pdf</b></code>
			<!-- updates Submodule -->
			<details>
				<summary><b>updates</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ pdf.updates</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/ChristianRodriguez46/Math4230-Final-Project/blob/master/pdf/updates/Ch04_Multiple_Linear_Regression.html'>Ch04_Multiple_Linear_Regression.html</a></b></td>
							<td style='padding: 8px;'>- Multiple Linear RegressionThis HTML file serves as an educational resource within the project, providing a comprehensive overview of multiple linear regression techniques<br>- It is part of a broader series aimed at teaching statistical modeling concepts, likely integrated into a larger data analysis or machine learning curriculum<br>- The content facilitates understanding of how multiple predictors can be used to model a response variable, supporting the projects goal of delivering accessible, well-structured learning materials on statistical methods and their applications.</td>
						</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
</details>

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

## Python Environment

This project was developed using:

```text
Python 3.14
```

The exact Python version is included so others know what environment the project was originally built with. However, the most important requirement is that the needed Python packages are installed.

Recommended Python version:

```text
Python 3.10 or newer
```

If you want to match my environment as closely as possible, use Python 3.14. If you already have Python 3.10, 3.11, 3.12, or 3.13 installed, the notebooks should still work as long as the required packages install correctly.

---

## Required Python Libraries

Install the following Python packages:

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
statsmodels
scipy
joblib
jupyter
notebook
ipykernel
openpyxl
```

You can install them all at once with:

```sh
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels scipy joblib jupyter notebook ipykernel openpyxl
```

---

## Setup Instructions for Linux / macOS

1. Clone the repository:

```sh
git clone https://github.com/ChristianRodriguez46/Math4230-Final-Project.git
```

2. Move into the project folder:

```sh
cd Math4230-Final-Project
```

3. Check your Python version:

```sh
python3 --version
```

This project was developed using Python 3.14, but Python 3.10 or newer should work if the required packages install correctly.

4. Create a virtual environment:

```sh
python3 -m venv .venv
```

5. Activate the virtual environment:

```sh
source .venv/bin/activate
```

6. Upgrade pip:

```sh
python -m pip install --upgrade pip
```

7. Install the required libraries:

```sh
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels scipy joblib jupyter notebook ipykernel openpyxl
```

8. Download the dataset from Kaggle:

```text
https://www.kaggle.com/datasets/ayeshasiddiqa123/student-health
```

9. Place the downloaded CSV file inside the `Datasets/` folder:

```text
Math4230-Final-Project/Datasets/student_mental_health_burnout_1M.csv
```

10. Start Jupyter Notebook:

```sh
jupyter notebook
```

11. Open the notebooks from the `notebooks/` folder.

---

## Setup Instructions for Windows

1. Clone the repository:

```powershell
git clone https://github.com/ChristianRodriguez46/Math4230-Final-Project.git
```

2. Move into the project folder:

```powershell
cd Math4230-Final-Project
```

3. Check your Python version:

```powershell
python --version
```

This project was developed using Python 3.14, but Python 3.10 or newer should work if the required packages install correctly.

4. Create a virtual environment:

```powershell
python -m venv .venv
```

5. Activate the virtual environment:

```powershell
.venv\Scripts\activate
```

6. Upgrade pip:

```powershell
python -m pip install --upgrade pip
```

7. Install the required libraries:

```powershell
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels scipy joblib jupyter notebook ipykernel openpyxl
```

8. Download the dataset from Kaggle:

```text
https://www.kaggle.com/datasets/ayeshasiddiqa123/student-health
```

9. Place the downloaded CSV file inside the `Datasets/` folder:

```text
Math4230-Final-Project\Datasets\student_mental_health_burnout_1M.csv
```

10. Start Jupyter Notebook:

```powershell
jupyter notebook
```

11. Open the notebooks from the `notebooks/` folder.

---

## Setup Instructions for WSL

If using Windows Subsystem for Linux, follow the Linux setup commands inside the WSL terminal.

Recommended workflow:

```sh
cd ~
git clone https://github.com/ChristianRodriguez46/Math4230-Final-Project.git
cd Math4230-Final-Project
python3 --version
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels scipy joblib jupyter notebook ipykernel openpyxl
jupyter notebook
```

Make sure the Kaggle dataset is placed inside:

```text
Math4230-Final-Project/Datasets/
```

---

## Running the Project

The notebooks should be run in chapter order because later chapters depend on files saved by earlier chapters.

Recommended order:

```text
1. Ch02_Dataset_Profile.ipynb
2. Ch03_Simple_Linear_Regression.ipynb
3. Ch04_Multiple_Linear_Regression.ipynb
4. Ch05_Logistic_Regression.ipynb
5. Ch06_Resampling_CV_Bootstrap.ipynb
6. Ch07_Regularization_Ridge_Lasso.ipynb
7. Ch08_Decision_Trees.ipynb
8. ch09_tree_ensembles.ipynb
9. ch10_support_vector_machines.ipynb
10. ch11_k_nearest_neighbors.ipynb
11. ch12_principal_component_analysis.ipynb
12. Ch13_Neural_Networks.ipynb
```

Chapter 2 creates the shared training, validation, and test files in the `results/` folder. Later chapters load those saved files.

Examples of saved files:

```text
results/X_train.npy
results/X_test.npy
results/X_val.npy
results/y_train_reg.npy
results/y_test_reg.npy
results/y_train_cls.npy
results/y_test_cls.npy
results/y_val_reg.npy
results/y_val_cls.npy
results/feature_names.pkl
results/standard_scaler.pkl
```

---

## Important Runtime Notes

Some notebooks may take longer than others.

The slowest notebooks are usually:

- Chapter 9: Tree Ensembles, especially gradient boosting tuning
- Chapter 10: Support Vector Machines
- Chapter 11: K-Nearest Neighbors
- Chapter 13: Neural Networks

Some cells save result files so they can be reused later without recomputing everything from scratch.

If a notebook has cached result-loading logic, it will first check whether the saved result already exists. If it exists, the notebook can load the file instead of rerunning the slow computation.

---

## Notes About Large Files

Large dataset files are not stored in this GitHub repository.

You must manually download the dataset from Kaggle and place it inside the `Datasets/` folder.

Dataset link:

```text
https://www.kaggle.com/datasets/ayeshasiddiqa123/student-health
```

This keeps the repository smaller and avoids GitHub file-size problems.

---

## Reproducibility

The notebooks use a fixed random seed where possible:

```python
RANDOM_STATE = 230
```

This helps keep train/test splits, samples, model tuning, and plots reproducible.

Some models may still have small differences depending on operating system, Python version, or library version.

---

## Testing and Validation

This project does not use a formal testing framework.

Validation is done through:

- train/test evaluation
- cross-validation
- bootstrap resampling
- out-of-bag error
- diagnostic plots
- saved result files
- repeated comparison across methods

---
---

<div align="left"><a href="#top">⬆ Return</a></div>

---
