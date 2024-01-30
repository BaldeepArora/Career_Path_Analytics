# Career-Path-Analytics

### Objective:
Understanding Salary Trends by Demographics and Experience

Using R to perform analysis and Visualization on data. Graphical representations are provided along with the code for the same. 

### Content Covered:

1. [Importing Libraries](#importing-Libraries)
2. [Handling missing values](#handling-missing-values)
3. [Exploratory Data Analysis](#EDA)<br>
       3.1. [Descriptive Statistics](#descriptive-statistics)<br>
       3.2. [Univariate Analysis](#univariate-analysis)<br>
       3.3. [Bivariate Analysis](#bivariate-analysis)

## 1. Importing Libraries
Below packages were installed and imported for this analysis:

       - readxl: Read and import Excel files into R.
       - ggplot2: Create static, animated, and interactive data visualizations in R.
       - dplyr: Perform data manipulation and transformation in R.
       - reshape2: Reshape and transform data in R.

## 2. Handling Missing Values
There are 6 features in the data:
<br> 1. Age
<br> 2. Gender
<br> 3. Education Level
<br> 4. Job Title
<br> 5. Years of Experience
<br> 6. Salary

Missing values in any row were observed and these rows were dropped before proceeding with Visualizations.

## 3. EDA
Exploratory Data Analysis on the cleaned data was performed.

![Summary Statistics](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Desriptive_Statistics.png)

Above shows the summary statistics of all the feature variable which contains in the data. With Min, Max, Mean, Median, 1st Quartile & 3rd Quartile of numerical features & number of entries of object variable.<br>
The numerical features are Age, years of experience and Salary. They are slightly skewed as there is difference between the mean and median in the data.<br>
The categorical features are Gender, Education Level and Job title.



### 3.1 Descriptive Statistics


### 3.2. Univariate Analysis


### 3.3. Bivariate Analysis
#### A. Top 10 highest paying Job Roles<br>
![Highest paying jobs](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Top%2010%20highest%20paying%20job%20roles.png)

This is a bar chart titled "Top 10 highest paying Job Roles". The x-axis represents different job titles, and the y-axis represents the average salary. The salaries in the dataset are below 250,000. The highest paying job in this dataset are CEO and Chief technology Officer at 250,000 each while the least paying jobs is Director of engineering.
       
#### B. Salary Distribution for job Roles with respect to Gender<br>
![Job Roles vs Gender](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Salary%20Distribution%20for%20job%20Roles%20with%20respect%20to%20Gender.png)

The median salary for both groups is above $100,000, with the median for the Female group being slightly lower than the Male group. The interquartile range (IQR) is narrower for the Female group compared to the Male group. This suggests that salaries for the Female group are more concentrated around the median, while the Male group has a more varied salary range. The upper quartile is higher for Males, which suggests that the salaries are higher. There are no visible outliers.

#### C. Salary Distribution for individuals with varying Educations<br>
![Salary vs Education](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Salary%20Distribution%20individuals%20with%20varying%20Educations.png)

Individuals with a PhD have higher salaries compared to those with a Master's or Bachelor's degree, as indicated by the position of the blue box (PhD) being generally higher on the salary axis. The median salary is also higher. The interquartile range (IQR) for PhD salaries is also larger, suggesting more variability in the salaries of individuals with a PhD. Individuals with a Bachelor's degree have the lowest median salary and the smallest IQR, indicating less variability in salaries compared to the other two education qualifications. There are several outliers for both the Master's and PhD categories, indicated by the dots outside the "whiskers" of the boxplots.


#### D. Scatterplot of Salary vs. Experience with Regression Line<br>
![Salary vs Experience](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Scatterplot%20of%20Salary%20vs.%20Experience%20with%20Regression%20Line.png)

There is a positive coerrelation between the age and salary. There is some variability around the regression line, indicating that while age is a factor, there are other factors that also affect salary since not all points fall directly on the line.


#### E. Scatterplot of Salary vs. Age with Regression Line<br>
![Salary vs Age](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Scatterplot%20of%20Salary%20vs.%20Age%20with%20Regression%20Line.png)

There is a positive correlation between years of experience and salary. The data points are more densely packed at the lower end of the experience scale, suggesting that there are more data entries for individuals with fewer years of experience. As experience increases, the data points spread out more, indicating a greater variance in salary at higher levels of experience. There are a few potential outliers, particularly at the higher end of the experience scale, where a small number of individuals have salaries that are significantly higher than others with similar experience.

#### F. Years of Experience vs Salary based on gender
![Experience vs Salary by Gender](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Years%20of%20Experience%20vs%20Salary%20based%20on%20gender.png)

There is a positive trend in the graph with a spread in salaries for both genders indicating an increase with experience, suggesting a wider range of salaries for individuals with more experience. There is no pattern in entry level experience. The highest salaries are for individuals with around 20-25 years of experience.
