# policesentiment
**PROJECT BACKGROUND**

As part of the Chicago Police Department's reform process, Chicago residents were delivered short surveys through digital ads. The surveys asked residents how safe they feel and how much trust they have in the police. Information collected also included demographics, including sex, race, education, and income level.

This project thoroughly analyzes and snythesizes this data in order to uncover critical insights that will improve the relationship between the Chicago Police Department and its citizens.

Insights and recommendations are provided on the following key areas:

**Sentiment Trends Analysis**: Evaluation of overall Safety, Trust, Listen, and Respect patterns over time.

**Demographics Impact on Sentiment Scores**: Impact of Race, Age, Education, and Income on Sentiment scores.

**Performance Analysis**: Is there a certain neighborhood or demographic that has higher Safety, Trust, Listen, and Respect scores over time.

An Interactive Excel dashboard with imputed data for missing values can be downloaded [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Scores%20with%20Imputed%20Data.png).

An Interactive Excel dashboard with no imputed data for missing values can be downloaded [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Scores%20without%20Imputed%20Data.png).

The Excel pivot tables utilized to organize and prepare data for the dashboard with imputed data can be found [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Scores%20with%20Imputed%20Data-Tables.xlsx).

The Excel pivot tables utilized to organize and prepare data for the dashboard without imputed data can be found [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Scores%20without%20Imputed%20Data-Tables.xlsx).

**DATA STRUCTURE & INITIAL CHECKS**

The Police Sentiment Scores dataset comprises a single table containing 7,558 records. Before initiating the analysis, a series of quality control procedures and exploratory checks were conducted to ensure data integrity and build familiarity with the dataset. The Excel queries used for these inspections and validations are available [here].

To understand the distribution of the data, a descriptive analysis was performed, including evaluations of skewness and kurtosis, which can be reviewed [here]. The distribution appeared approximately normal, with a couple of skewness and kurtosis values falling between 0.50 and 1.0 and -0.50 and -1.0, respectively.

While several columns contain missing data, the pattern appears structured rather than random. To address this, two dashboards were developed: one incorporates imputed values for the missing data, while the other retains the original dataset without imputation. Given the normality of the distribution, the mean was selected as the imputation method.

The image below shows some of the columns of interest including overall Safety, Trust, Listen, and Respect. It also shows Safety, Trust, Listen, and Respect scores for each race, gender, income, and educational level. 

![Image](https://github.com/user-attachments/assets/b2c08ab9-31ac-46f5-9dba-d9ca10cdf83c)

**EXECUTIVE SUMMARY**

OVERVIEW OF FINDINGS
