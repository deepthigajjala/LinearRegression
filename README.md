🎈🎈#LINEAR REGRESSION🎈🎈
##BUSINESS PROBLEM:
  Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
  They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.
  Your analysis will help Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.

## MY ANALYSIS:
1. I imported the data and checked dataset has 500 rows and 9 columns.
2. I dropped umimportant columns. I Divided columns into discrete and continuus columns. For each discrete column I checked no.of unique values.
3. I checked variation of all continuous columns with discrete columns.
4. I did Univariate and Bivariate Analysis.
5. By using HeatMap I checked existence of Multicollinearity between CGPA,TOEFL and GRE score.
6. By seeing the Boxplots, I conclude the existence of Ouliers. By using IQR Method I removed the outliers.
7. Standardised the data using StandardScaler.
8. Splitted into training and test data using Train-test split.
9. I trained the data using Training data.
10 By using Statmodels Linear Regression I got 0.851 Adj R-squared value.
11.By using Sklearn Linear Regression I got 0.81 as model score.
12.I concluded that there is no Hetreoscadicity as Residuals are not varying a lot.
13. I checked multicollinearity by using VIF value of each column

