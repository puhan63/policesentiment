# policesentiment
**PROJECT BACKGROUND**

As part of the Chicago Police Department's reform process, Chicago residents were delivered short surveys through digital ads. The surveys asked residents how safe they feel and how much trust they have in the police. Information collected also included demographics, including sex, race, education, and income level.

This project thoroughly analyzes and snythesizes this data in order to uncover critical insights that will improve the relationship between the Chicago Police Department and its citizens.

Insights and recommendations are provided on the following key areas:

**Sentiment Trends Analysis**: Evaluation of overall Safety, Trust, Listen, and Respect patterns over time.

**Demographics Impact on Sentiment Scores**: Impact of Race, Age, Education, and Income on Sentiment scores.

**Performance Analysis**: Is there a certain neighborhood or demographic that has higher Safety, Trust, Listen, and Respect scores over time.

An Interactive Tableau dashboard with imputed data for missing values can be downloaded [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Scores.twbx).

An Interactive Tableau dashboard with no imputed data for missing values can be downloaded [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20with%20Missing%20Data.twbx).

The Tableau formulas utilized to organize and prepare data for the dashboard can be found [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Formula.xlsx).

**DATA STRUCTURE & INITIAL CHECKS**

The Police Sentiment Scores dataset comprises a single table containing 7,558 records. Before initiating the analysis, a series of quality control procedures and exploratory checks were conducted to ensure data integrity and build familiarity with the dataset. The Excel queries used for these inspections and validations are available [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Missing%20Data%20Analysis.xlsx).

To understand the distribution of the data, a descriptive analysis was performed, including evaluations of skewness and kurtosis, which can be reviewed [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Descriptive%20Statistics.xlsx). The distribution appeared approximately normal, with a couple of skewness and kurtosis values falling between 0.50 and 1.0 and -0.50 and -1.0, respectively.

While several columns contain missing data, the pattern appears structured rather than random. To address this, two dashboards were developed: one incorporates imputed values for the missing data, while the other retains the original dataset without imputation. Given the normality of the distribution, the mean was selected as the imputation method.

The image below shows some of the columns of interest including overall Safety, Trust, Listen, and Respect. It also shows Safety, Trust, Listen, and Respect scores for each race, gender, income, and educational level. 

![Image](https://github.com/user-attachments/assets/b2c08ab9-31ac-46f5-9dba-d9ca10cdf83c)

**EXECUTIVE SUMMARY**

OVERVIEW OF FINDINGS

Sentiment scores for Safety, Trust, Listening, and Respect were highest in 2018. While scores for Listening and Respect remained elevated in 2019, they gradually declined in subsequent years.

Below is part of the Tableau dashboard reflecting overall sentiment scores. More examples are included throughout the report. The entire interactive dashboard canbe downloaded [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Scores.twbx).

**By location**, sentiment scores peaked in Area_3 and were consistently lowest in the SOUTH region across all racial groups.

**By education**, Respect received the highest sentiment ratings across all education levels, though scores declined as education levels increased.

**By age**, sentiment scores for Respect, Trust, and Listening tended to decrease with age. Respect scores were highest among the middle and older age groups, while Safety scored highest among the youngest group.

**By gender**, males reported higher sentiment scores across all categories compared to females.

**By income**, individuals with higher incomes showed the highest sentiment scores across all categories, followed by those with medium and then low income levels.

