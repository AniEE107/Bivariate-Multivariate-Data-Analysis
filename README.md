# Bivariate-Multivariate-Data-Analysis
This Jupyter Notebook explores bivariate and multivariate relationships across various datasets (Titanic, Iris, Flights, Restaurants). It demonstrates using Pandas and Seaborn for comprehensive data visualization and statistical analysis to uncover hidden patterns and insights.

#  Overview & Purpose
This Jupyter Notebook serves as a practical guide to exploratory data analysis (EDA), with a specific focus on understanding bivariate and multivariate relationships within various datasets. In data science, it's crucial to not only analyze individual variables but also to uncover how different variables interact with each other. This project demonstrates various visualization and statistical techniques to achieve this, helping to identify patterns, correlations, and potential insights that are not apparent from univariate analysis alone.

# The primary purpose is to:
Illustrate Relational Analysis: Show how to effectively visualize and interpret relationships between two (bivariate) or more (multivariate) variables.
Showcase EDA Techniques: Provide examples of common plots and statistical methods used in EDA for different data types.
Apply to Diverse Datasets: Demonstrate these techniques across multiple real-world datasets (Titanic, Iris, Restaurants, Flights) to highlight their versatility.

#  Key Concepts & Functionality
The notebook covers a range of techniques and visualizations, including but not limited to:
Data Loading: Importing various datasets (titanic_csv.csv, iris_csv.csv, restaurants.csv, flights.csv) using Pandas.
Basic Data Inspection: Initial checks for missing values (.isnull().sum()) and descriptive statistics (.describe()).

# Bivariate Analysis:

Scatter Plots: To visualize relationships between two numerical variables.
Box Plots/Violin Plots: To compare numerical distributions across different categories.
Count Plots/Bar Plots: To compare frequencies or aggregated values across categories.
Joint Plots/Pair Plots: For comprehensive pairwise relationships.

# Multivariate Analysis:

Heatmaps (Correlation Matrices): To show correlations between multiple numerical variables.
Grouped Bar/Box Plots: To visualize relationships involving more than two variables by adding a third categorical dimension.
Pivot Tables: For summarizing data by multiple dimensions (.pivot_table()).
Facet Grids: To create grids of plots based on different subsets of data, allowing for comparison across multiple variables.

#  Technologies Used
Python
Pandas (for data manipulation and analysis)
Seaborn (for advanced statistical data visualization)
Matplotlib (for basic plotting and plot customization)
Jupyter Notebook
