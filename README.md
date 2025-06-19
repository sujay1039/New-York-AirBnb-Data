# New York AirBnB Data Analysis

Objective
The objective of this project is to perform Exploratory Data Analysis (EDA) on the New York City AirBnB dataset to understand patterns in pricing, availability, and neighborhood popularity. The analysis helps stakeholders such as hosts, tourists, and analysts make informed decisions.

Goals of the Project
- Understand how AirBnB listings vary across different neighborhoods.
- Analyze the price distribution and what factors affect price.
- Explore the availability of listings throughout the year.
- Identify outliers and missing data.
- Make the dataset clean and analysis-ready.

Tools & Libraries Used
- Python	Main programming language
- Pandas	Data manipulation and cleaning
- NumPy	Numerical operations
- Matplotlib & Seaborn	Data visualization
- Jupyter Notebook	Interactive code and markdown writing

Key Terms Explained
- EDA (Exploratory Data Analysis), The process of analyzing data sets by summarizing their main characteristics using visual methods.
- Null/None/NaN	Represents missing or undefined values in the dataset.
- GroupBy	A method in Pandas to group data and perform operations like sum, mean, etc., on those groups.
- Object Data Type	In Pandas, represents text or mixed values (e.g., a column with both numbers and letters).
- Heatmap	A color-coded matrix to visualize relationships (like correlations) between multiple variables.
- Bins (in Histogram)	Intervals into which data is divided for frequency distribution (e.g., age 0–10, 11–20, etc.).
- Annot	In visualizations (especially heatmaps), it enables display of values inside the plot cells.

What We Did (Step-by-Step)
- Loaded the dataset and checked for structure, types, and missing values.
Cleaned the data by:
- Dropping unnecessary columns like name, host_name, last_review
- Filling or removing NaN values in columns like reviews_per_month
Analyzed distributions using:
- Histograms (for price, availability)
- Countplots (for room types and neighbourhoods)
- Visualized correlations using heatmaps.
- Used groupby to summarize price and availability by neighborhood.
- Filtered outliers to prevent them from skewing analysis.

Outcomes / Results
- Manhattan has the highest number of listings and the most expensive prices on average.
- Entire home/apt is the most common room type in popular neighborhoods.
- Price distribution is skewed with many low-priced listings and a few high-priced outliers.
- Several entries had missing review data, which was cleaned to avoid errors.
- Visualizations clearly highlighted how room type and location impact pricing.

Conclusion
This analysis helps understand how various factors like location, room type, and availability influence AirBnB listing prices in New York. With clean data and compelling visualizations, this project offers valuable insights for hosts, tourists, and data analysts alike.
