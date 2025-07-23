# Titanic-Survival-Analysis
Comprehensive EDA of Titanic dataset using Python (pandas, numpy, matplotlib, seaborn) to uncover key factors influencing passenger survival during the sinking. Demonstrates data cleaning, analysis, and insightful visualization techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Goal](#goal)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Key Findings & Visualizations](#key-findings-visualizations)
- [Technologies Used](#technologies-used)
- [Installation & Usage](#installation-usage)
- [Contact](#contact)

---

## Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on the famous Titanic dataset to understand factors influencing survival, followed by (optional) building a machine learning model to predict passenger survival. The analysis covers data cleaning, visualization, and insightful observations about demographics and survival rates.

## Goal
The primary motivation behind this project was to practice core data science skills, including data loading, cleaning, manipulation, and visualization using Python's data analysis libraries. The goal was to uncover patterns in passenger demographics and their correlation with survival on the Titanic, demonstrating proficiency in data exploration and interpretation.

## Dataset
The dataset used is the widely known "Titanic - Machine Learning from Disaster" dataset, obtained from Kaggle [page 1]. It contains information about Titanic passengers, including `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, and `Embarked`.

## Exploratory Data Analysis (EDA)
The EDA process involved:
-   **Initial Data Inspection:** Using `df.head()`, `df.tail()`, `df.info()`, `df.shape`, and `df.columns` to understand the data structure and types.
-   **Descriptive Statistics:** Analyzing numerical and categorical features using `df.describe()` and `df.describe(include="object")`.
-   **Missing Value Handling:** Identifying and addressing missing values in `Age`, `Cabin`, and `Embarked` by imputation (mean for Age, mode for Embarked) and dropping `Cabin` due to high missingness.
-   **Univariate Analysis:** Visualizing distributions of `Sex`, `Pclass`, `Age`, and `Fare` using count plots, histograms, and box plots.
-   **Bivariate Analysis:** Exploring relationships between `Sex`, `Pclass`, `Age`, `Fare` and `Survived` using bar plots and stacked histograms/box plots.

## Key Findings & Visualizations
-   **Gender played a significant role in survival:** Females had a significantly higher survival rate than males.
-   **Passenger Class Impact:** First-class passengers had a much higher survival rate compared to second and especially third-class passengers.
-   **Age Distribution & Survival:** The Age distribution showed a peak around 20-40, and survival rates varied across age groups, with potentially higher survival for younger children and lower for certain older age groups.
-   Visualizations like "Survival Rate by Sex," "Survival Rate by Passenger Class," "Age Distribution by Survival Status," and "Fare Distribution by Survival Status" are integral to understanding these finding.

## Technologies Used
-   Python 3.9.6
-   `pandas` (for data manipulation and analysis)
-   `numpy` (for numerical operations)
-   `matplotlib` (for plotting and visualization)
-   `seaborn` (for enhanced statistical visualizations)
-   Power BI (for visualizing the insights)

## Installation & Usage
To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AHMEDM0369/Titanic-Survival-Analysis.git
    cd Titanic-Survival-Analysis
    ```
2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook notebooks/CODECRAFT_DS_02.ipynb 
    ```

## Contact
-   Your Name - ahmedm
-   Your Email - mrahmedm09@gmail.com
