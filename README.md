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
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)
- [Features](#features)
- [Project Structure](#project-structure)
    - [Project Index](#project-index)

---

## Overview

Math4230-Final-Project is a versatile developer toolkit designed to facilitate the development, analysis, and visualization of machine learning models. It combines educational notebooks with practical tools to support robust, interpretable, and scalable data science workflows. Whether you're exploring data, building predictive models, or validating results, this project provides a solid foundation for advanced ML development.

**Why Math4230-Final-Project?**

This project aims to streamline your machine learning journey with core features including:

- 🧩 **Modular Notebooks:** Covering techniques from linear regression to neural networks, supporting both learning and deployment.
- 🌟 **Data Profiling & Validation:** Tools for dataset analysis and model evaluation to ensure reliability.
- 🧠 **Interpretability Focus:** Emphasizes transparent models like decision trees and regularization methods.
- 🚀 **Open-Source Collaboration:** Encourages community contributions and customization for diverse use cases.
- 🎯 **Educational & Practical:** Bridges theoretical concepts with real-world applications for developers and data scientists alike.

---

## Features

|      | Component       | Details                                                                                     |
| :--- | :-------------- | :------------------------------------------------------------------------------------------ |
| ⚙️  | **Architecture**  | <ul><li>Jupyter Notebook-based workflows for data analysis and modeling</li><li>Modular code organized into separate notebooks and scripts</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Consistent use of Python conventions within notebooks</li><li>Some inline comments, but limited modularization</li></ul> |
| 📄 | **Documentation** | <ul><li>Basic README with project overview</li><li>Embedded markdown cells in notebooks explaining steps</li><li>Limited external documentation or API references</li></ul> |
| 🔌 | **Integrations**  | <ul><li>Uses datasets from external files ('dataset - short descriptions.txt')</li><li>HTML outputs for visualization or reporting</li><li>License info embedded in notebooks</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Notebooks segmented by tasks (data loading, analysis, visualization)</li><li>Some functions defined for reuse within notebooks</li></ul> |
| 🧪 | **Testing**       | <ul><li>No formal testing framework detected</li><li>Potential manual validation within notebooks</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Limited optimization; primarily data processing and visualization</li><li>No parallelization or performance profiling evident</li></ul> |
| 🛡️ | **Security**      | <ul><li>No security features or measures implemented</li><li>Data handling appears local and non-sensitive</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Python dependencies: 'jupyternotebook'</li><li>Supporting files: 'html', 'license', dataset descriptions</li></ul> |

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
					<td style='padding: 8px;'>- SummaryThis notebook demonstrates the application of resampling techniques, including cross-validation and bootstrap methods, to evaluate and improve model performance<br>- It serves as a practical guide within the broader project architecture to ensure robust model validation, helping to prevent overfitting and assess the generalization capability of machine learning models across different datasets and scenarios<br>- This aligns with the projects goal of building reliable, well-validated predictive models within the overall data science workflow.</td>
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
					<td style='padding: 8px;'>- SummaryThis Jupyter notebook serves as an instructional guide within the project, demonstrating how regularization techniques—specifically Ridge and Lasso regression—are applied to improve model performance and prevent overfitting<br>- It fits into the broader architecture by illustrating key concepts of model regularization, complementing other modules focused on data preprocessing, feature engineering, and model evaluation<br>- Overall, this notebook enhances the understanding of regularization methods as essential tools for building robust, generalizable machine learning models within the project.---</td>
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

- **Programming Language:** JupyterNotebook

### Installation

Build Math4230-Final-Project from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/ChristianRodriguez46/Math4230-Final-Project
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd Math4230-Final-Project
    ```

3. **Install the dependencies:**

echo 'INSERT-INSTALL-COMMAND-HERE'

### Usage

Run the project with:

echo 'INSERT-RUN-COMMAND-HERE'

### Testing

Math4230-final-project uses the {__test_framework__} test framework. Run the test suite with:

echo 'INSERT-TEST-COMMAND-HERE'

---

<div align="left"><a href="#top">⬆ Return</a></div>

---
