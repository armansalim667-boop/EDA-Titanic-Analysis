Task 2: Exploratory Data Analysis (EDA)
Objective: Understand a dataset using statistics and visualizations.

Tools:
Pandas
Matplotlib
Seaborn
Plotly

What you have to do

1. Generate summary statistics
Find:
Mean
Median
Standard Deviation
Min and Max values
Example:
Python
df.describe()

2. Create Histograms and Boxplots
Histogram shows how data is distributed.
Python
plt.hist(df['Age'])
plt.show()
Boxplot helps detect outliers.
Python
sns.boxplot(x=df['Fare'])
plt.show()

3. Use Pairplot or Correlation Matrix
Pairplot:
Python
sns.pairplot(df)
Correlation Matrix:
Python
sns.heatmap(df.corr(numeric_only=True), annot=True)
These show relationships between features.

4. Identify Patterns and Trends
Examples for Titanic dataset:
Females survived more than males.
First-class passengers survived more often.
Higher ticket fare often meant higher survival chances.

5. Make Inferences
Write conclusions such as:
Most passengers were between 20–40 years old.
Fare column contains outliers.
Female passengers had a higher survival rate.

Key Findings:

1. Age contains missing values.
2. Cabin has many missing values.
3. Most passengers were aged 20–40 years.
4. Fare has several outliers.
5. Females survived more than males.
6. Higher-class passengers had better survival rates.
