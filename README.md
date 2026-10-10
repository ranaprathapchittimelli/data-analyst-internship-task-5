# Task 5: Exploratory Data Analysis (EDA) - Titanic Dataset

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset as part of a Data Analyst Internship task.

The main objective is to analyze passenger data, identify patterns and trends, examine missing values, detect potential outliers, and understand the factors associated with passenger survival.

## Objectives
- Understand the dataset structure and data types.
- Perform descriptive statistical analysis.
- Identify missing values and duplicate records.
- Analyze passenger age and ticket fare distributions.
- Compare survival rates by gender and passenger class.
- Explore correlations between numerical variables.
- Visualize findings using charts and graphs.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Description
The Titanic dataset contains passenger information, including:

- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

**Dataset size:** 891 rows and 12 columns.

## Data Analysis Performed
1. Dataset inspection using `head()`, `info()`, and `describe()`.
2. Missing-value analysis using `isnull().sum()`.
3. Survival count analysis using `value_counts()`.
4. Age distribution using a histogram.
5. Fare outlier detection using a boxplot.
6. Survival rate comparison by gender.
7. Survival rate comparison by passenger class.
8. Scatterplot analysis of age and fare.
9. Correlation heatmap.
10. Pairplot for relationships between numerical variables.

## Key Findings
- Total passengers analyzed: 891.
- Total survivors: 342.
- Total passengers who did not survive: 549.
- Overall survival rate: 38.38%.
- Age has 177 missing values.
- Cabin has 687 missing values.
- Embarked has 2 missing values.
- Survival rates differ across gender and passenger classes.
- The fare distribution contains potential outliers.

## Conclusion
Exploratory Data Analysis helped identify missing data, understand variable distributions, detect potential outliers, and explore relationships between passenger characteristics and survival.

The visualizations and statistical summaries provide useful insights into the Titanic dataset. These findings are descriptive and do not establish causation.

## Project Files
- `Task5_Titanic_EDA.ipynb` – Jupyter Notebook containing the analysis and visualizations.
- `train.csv` – Titanic dataset used for analysis.
- `Task5_EDA_Report.pdf` – PDF report containing the findings.
- `visualizations/` – Graph images generated during the analysis.

## How to Run
1. Download or clone this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Open a terminal in the project folder.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Task5_Titanic_EDA.ipynb` and run the cells in order.

## Internship Task
**Task 5: Exploratory Data Analysis (EDA)**

**Tools:** Python, Pandas, Matplotlib, Seaborn.
