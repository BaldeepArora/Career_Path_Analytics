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
       
       #### B. Salary Distribution for job Roles with respect to Gender<br>
       ![Job Roles vs Gender](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Salary%20Distribution%20for%20job%20Roles%20with%20respect%20to%20Gender.png)

       
       #### C. Salary Distribution for individuals with varying Educations<br>
       ![Salary vs Education](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Salary%20Distribution%20individuals%20with%20varying%20Educations.png)
       
       #### D. Scatterplot of Salary vs. Experience with Regression Line<br>
       ![Salary vs Experience](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Scatterplot%20of%20Salary%20vs.%20Experience%20with%20Regression%20Line.png)
       
       #### E. Scatterplot of Salary vs. Age with Regression Line<br>
       ![Salary vs Age](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Scatterplot%20of%20Salary%20vs.%20Age%20with%20Regression%20Line.png)
       
       #### F. Years of Experience vs Salary based on gender
       ![Experience vs Salary by Gender](https://github.com/BaldeepArora/Career_Path_Analytics/blob/main/Years%20of%20Experience%20vs%20Salary%20based%20on%20gender.png)


