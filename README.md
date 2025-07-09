# 🌍 World Population EDA with Pandas

This project performs an exploratory data analysis (EDA) on a dataset containing historical population data across different countries and continents from 1970 to 2022.

## 📁 Dataset

- **File Name:** `world_population(1).csv`
- **Source:** Contains population data by country and continent for multiple decades.

## 📊 Tools & Libraries

- Python
- Pandas
- Seaborn
- Matplotlib

## 📌 Key Steps in the Analysis

1. **Loading and inspecting data**
   - Used `pandas.read_csv()` to load the dataset.
   - Displayed basic info using `df.info()`, `df.describe()`, and `df.isnull().sum()`.

2. **Data Configuration**
   - Set display options for better readability using `pd.set_option()`.

3. **Data Exploration**
   - Counted unique values with `df.nunique()`.
   - Sorted and viewed top 10 countries by 2022 population.
   - Grouped and analyzed average population by continent.
   - Transposed grouped data for temporal comparison.
   - Filtered specific continents like Oceania.

4. **Data Visualization**
   - Heatmap of population correlations using Seaborn.
   - Line plots to show population trends by continent.
   - Boxplot to detect outliers in population distribution.

5. **Data Typing and Structure**
   - Identified object vs numeric columns.
   - Used `.select_dtypes()` and `.dtypes` for better column handling.

## 📈 Insights

- Asia and Africa have seen the most significant population growth.
- The 2022 population correlates highly with previous years.
- There are some clear outliers in the dataset, visualized using boxplots.
- Oceania has the smallest average population among all continents.
