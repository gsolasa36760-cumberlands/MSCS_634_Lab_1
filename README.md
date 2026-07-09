# MSCS_634_Lab_1
## Lab 1: Data Visualization, Data Preprocessing, and Statistical Analysis Using Python in Jupyter Notebook

### Purpose of the Lab

The purpose of this lab was to apply data visualization, data preprocessing, and statistical analysis techniques using Python in Jupyter Notebook. Data characteristics were investigated by applying a dataset of supermarket sales to be used for meaningful visualisations, data quality checks, data transformations and data descriptors for detailed data analysis.

### Key Insights from Visualizations and Statistical Measures

The visualization presented the various trends for sales, distribution of sales across product lines, a positively skewed distribution of gross income with some outlier values, and a relatively even distribution of customer payment method. The results of statistical analysis indicated that sales and pricing variables were moderately varying, that there were strong positive correlations among some of the sales related variables (Tax, Gross Income, Cost of Goods Sold), and that there were weak correlations between the customer ratings and other numerical variables. Data preprocessing revealed that there were no missing values in the data and that some identified outliers were excluded, reducing the size of the data and making the result more efficient for analysis.

### Challenges and Decisions

The data set was checked for missing data with the appropriate detection methods and the analysis showed that there was no missing data in any attribute. No missing value imputation or treatment was, therefore, necessary. The outlier detection method used was Inter Quartile Range (IQR) because it is effective in detecting outliers without the assumption of any data distribution. Random sampling and feature elimination were used to reduce the size of the dataset while preserving the important information. Min-Max Scaling was chosen to scale numerical variables to a similar range and maintain relationships between observations.
