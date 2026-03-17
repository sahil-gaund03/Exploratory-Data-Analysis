Roller Coaster Data Analysis & EDA
This project involves a comprehensive Exploratory Data Analysis (EDA) of a roller coaster dataset (coaster_name.csv). The analysis focuses on data cleaning, feature understanding, and uncovering relationships between different coaster attributes like speed, height, and year introduced.

🚀 Project Workflow
1. Data Understanding & Preparation
Initial Inspection: Reviewing data shape, columns, and data types (e.g., converting Opening Date to datetime).

Data Cleaning:

Dropping irrelevant or redundant columns (e.g., multiple height/speed units).

Renaming columns for readability (e.g., coaster_name, Location, Year_Introduced).

Handling missing values and duplicates (specifically focusing on duplicate coaster_name).

2. Feature Understanding (Univariate Analysis)
Analysis of individual variables using:

Bar Charts: Identifying the top years when the most roller coasters were introduced.

Histograms & KDE Plots: Visualizing the distribution of coaster speeds and heights.

3. Feature Relationships (Bivariate/Multivariate Analysis)
Exploring how variables interact:

Scatter Plots: Comparing Speed vs. Height and Year Introduced.

Heatmaps: Visualizing the correlation matrix between numerical features.

Pairplots: Understanding multifaceted relationships across the entire dataset, segmented by coaster type (e.g., Wood vs. Steel).

📊 Key Insights
The analysis identifies the most prolific years for roller coaster construction.

Correlation analysis reveals the direct relationship between a coaster's height and its top speed.

The data is segmented to compare physical attributes across different coaster locations and material types.

🛠️ Requirements & Dependencies
To run this notebook, you will need:

Python 3.x

pandas: Data manipulation and cleaning.

numpy: Numerical operations.

matplotlib / seaborn: Data visualization (using the ggplot style).

Install the dependencies:

Bash
pip install pandas numpy matplotlib seaborn
📈 Visualizations Included
The notebook generates several "publication-quality" plots using Seaborn:

Top 10 Years Coasters Introduced (Bar Plot)

Coaster Speed Distribution (Histogram with Kernel Density Estimate)

Speed vs. Height Correlation (Scatter Plot)

Correlation Heatmap (Matrix of numerical features)

Author
Sahil First-year student at Elphinstone College, Mumbai IBM Certified in Python for Data Science & AI

Note: This project demonstrates proficiency in data cleaning and statistical visualization using the Python data science stack.
