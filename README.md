# Titanic Missing Values Analysis

This repository is part of a university project focused on analyzing and handling missing values in the Titanic dataset, as well as visualizing survival patterns through an interactive Power BI dashboard.

## Project Description

The goal of the project was to identify, analyze, and propose methods for handling missing data in various columns of the Titanic dataset. The analysis includes:

- Identifying the presence and nature of missing values
- Understanding which variables are affected
- Determining whether the missing data is random or informative
- Visualizing distributions (e.g., age)
- Making decisions on how to handle missing data: deletion, imputation, or transformation

The project is written in Polish and includes an English version of the notebook for international readability.

## Power BI Dashboard

In addition to the Jupyter notebook, the repository includes a Power BI dashboard that provides an interactive visual summary of key insights.

---

### Features:

- Survival rate by sex and class
- Age distribution of survivors
- Impact of deck (extracted from cabin) on survival
- Total passenger count, survival rate, average age
- Interactive slicers for filtering by class, sex, and embarkation point

---

## Technologies Used

- **Python** – data analysis & preprocessing
  - Pandas
  - NumPy
  - Matplotlib
- **Jupyter Notebook** – for exploratory data analysis
- **Power BI** – dashboard visualization

---

## How to run

### Notebook 

1. Clone the repo
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Open the notebook in Jupyter or VS Code

### See the notebook here: 

[Titanic_Missing_Values_EN.ipynb](Titanic_Missing_Values_EN.ipynb)

[Titanic_Missing_Values_PL.ipynb](Titanic_Missing_Values.ipynb)

### Power BI

To view the dashboard:

1. Download and install Power BI Desktop
2. Open Titanic_Dashboard.pbix

### Power BI file: 
[Titanic_SurvivalRate.pbix](Titanic_SurvivalRate.pbix)

### Preview:
![obraz](https://github.com/user-attachments/assets/dc23fcc9-fc8a-4af1-ac9e-27f88059e142)


---

## Data

This project uses a variant of the Titanic dataset for educational purposes, as part of university coursework.  
The dataset includes information about passengers (age, class, sex, survival, cabin, etc.) and is used to explore handling of missing data.
If you are the original author or distributor and would like to be credited or have the file removed, please contact me.
