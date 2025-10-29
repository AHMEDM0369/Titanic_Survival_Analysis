# Titanic_Survival_Analysis
Comprehensive EDA of Titanic dataset using Python (pandas, numpy, matplotlib, seaborn) to uncover key factors influencing passenger survival during the sinking. Demonstrates data cleaning, analysis, and insightful visualization techniques.


Comprehensive Exploratory Data Analysis (EDA) of the Titanic dataset using Python (`pandas`, `numpy`, `matplotlib`, `seaborn`) to uncover key factors influencing passenger survival during the Titanic disaster. Demonstrates data cleaning, analysis, and insightful visualization techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Goal](#goal)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Key Findings & Visualizations](#key-findings--visualizations)
- [Technologies Used](#technologies-used)
- [Installation & Usage](#installation--usage)
- [Contact](#contact)

## Project Overview
This project conducts an in-depth Exploratory Data Analysis (EDA) on the Titanic dataset to identify factors influencing passenger survival. The analysis includes data cleaning, visualization, and deriving insights about demographics and survival patterns. Optionally, a machine learning model can be built to predict survival based on the findings.

## Goal
The primary objective is to practice essential data science skills, including data loading, cleaning, manipulation, and visualization using Python's data analysis libraries. The project aims to uncover patterns in passenger demographics (e.g., gender, class, age) and their correlation with survival, showcasing proficiency in data exploration and interpretation.

## Dataset
The dataset used is the "Titanic - Machine Learning from Disaster" dataset from Kaggle. It includes passenger information such as `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, and `Embarked`.

## Exploratory Data Analysis (EDA)
The EDA process includes:
- **Initial Data Inspection:** Using `df.head()`, `df.tail()`, `df.info()`, `df.shape`, and `df.columns` to understand data structure and types.
- **Descriptive Statistics:** Analyzing numerical and categorical features with `df.describe()` and `df.describe(include="object")`.
- **Missing Value Handling:** Addressing missing values in `Age` (imputed with mean), `Cabin` (dropped due to high missingness), and `Embarked` (imputed with mode).
- **Univariate Analysis:** Visualizing distributions of `Sex`, `Pclass`, `Age`, and `Fare` using count plots, histograms, and box plots.
- **Bivariate Analysis:** Exploring relationships between `Sex`, `Pclass`, `Age`, `Fare`, and `Survived` using bar plots, stacked histograms, and box plots.

## Key Findings & Visualizations
- **Gender and Survival:** Females had a significantly higher survival rate than males.
- **Passenger Class Impact:** First-class passengers had a higher survival rate compared to second- and third-class passengers.
- **Age and Survival:** Age distribution peaks around 20–40 years, with higher survival rates for younger children and varying rates across older groups.
- Visualizations include "Survival Rate by Sex," "Survival Rate by Passenger Class," "Age Distribution by Survival Status," and "Fare Distribution by Survival Status."

## Technologies Used
- Python 3.9.6
- `pandas` (data manipulation and analysis)
- `numpy` (numerical operations)
- `matplotlib` (plotting and visualization)
- `seaborn` (enhanced statistical visualizations)
- Power BI (for visualizing insights)

## Installation & Usage
To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/AHMEDM0369/Titanic_Survival_Analysis.git
    cd Titanic_Survival_Analysis
    ```
2. **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4. **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook Titanic_Survival_Analysis.ipynb
    ```

## Contact
-   Name - ahmedm
-   Email - mrahmedm09@gmail.com
