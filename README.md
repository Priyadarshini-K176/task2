# task2

# Titanic Data Analysis - Task 2

This notebook explores the Titanic dataset using basic data visualization techniques to identify patterns and insights related to passenger demographics and survival.

## 🔍 Tasks Performed

- Loaded Titanic dataset into a pandas DataFrame
- Performed exploratory data analysis (EDA) on key features:
  - **Fare**: Visualized with histogram to observe skewed distribution
  - **Age**: KDE plots to understand age spread
  - **Survival Trends**:
    - Age vs Survival using `sns.kdeplot()` with `hue='Survived'`
    - Planned: Survival distribution by gender using countplot/barplot

## 📊 Key Insights

- **Fare** is highly right-skewed; most passengers paid low fares.
- **Age** distribution peaks around 20–30 years.
- **Children (age < 10)** had a higher chance of survival.
- Planned next: Visualize survival rates across gender and class (`Sex`, `Pclass`).

## 🛠️ Tools Used

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Git for version control

## 📁 File

- `task2.ipynb` – contains all code and visuals.

