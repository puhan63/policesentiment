# policesentiment
**PROJECT BACKGROUND**

As part of the Chicago Police Department's reform process, Chicago residents were delivered short surveys through digital ads. The surveys asked residents how safe they feel and how much trust they have in the police. Information collected also included demographics, including sex, race, education, and income level.

This project thoroughly analyzes and snythesizes this data in order to uncover critical insights that will improve the relationship between the Chicago Police Department and its citizens.

Insights and recommendations are provided on the following key areas:

**Sentiment Trends Analysis**: Evaluation of overall Safety, Trust, Listen, and Respect patterns over time.

**Demographics Impact on Sentiment Scores**: Impact of Race, Age, Education, and Income on Sentiment scores.

**Performance Analysis**: Is there a certain neighborhood or demographic that has higher Safety, Trust, Listen, and Respect scores over time.

An Interactive Tableau dashboard with imputed data for missing values can be downloaded [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20New%20Dashboard.twbx).

An Interactive Tableau dashboard with no imputed data for missing values can be downloaded [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Missing%20Data%20Dashboard.twbx).

**DATA STRUCTURE & INITIAL CHECKS**

The Police Sentiment Scores dataset comprises a single table containing 7,558 records. Before initiating the analysis, a series of quality control procedures and exploratory checks were conducted to ensure data integrity and build familiarity with the dataset. The Excel queries used for these inspections and validations are available [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Missing%20Data%20Analysis.xlsx).

To understand the distribution of the data, a descriptive analysis was performed, including evaluations of skewness and kurtosis, which can be reviewed [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20Descriptive%20Statistics.xlsx). The distribution appeared approximately normal, with a couple of skewness and kurtosis values falling between 0.50 and 1.0 and -0.50 and -1.0, respectively.

While several columns contain missing data, the pattern appears structured rather than random. To address this, two dashboards were developed: one incorporates imputed values for the missing data, while the other retains the original dataset without imputation. Given the normality of the distribution, the mean was selected as the imputation method.

The image below shows some of the columns of interest including overall Safety, Trust, Listen, and Respect. It also shows Safety, Trust, Listen, and Respect scores for each race, gender, income, and educational level. 

![Image](https://github.com/user-attachments/assets/b2c08ab9-31ac-46f5-9dba-d9ca10cdf83c)

**EXECUTIVE SUMMARY**

OVERVIEW OF FINDINGS

Sentiment scores for Safety, Trust, Listening, and Respect were highest in 2018. While scores for Listening and Respect remained elevated in 2019, they gradually declined in subsequent years. Sentiment scores peaked in Area_3 and were consistently lowest in the SOUTH region. No data was collected from the North, South, or Central regions between 2020 and 2023.

Below is part of the Tableau dashboard reflecting overall sentiment scores. More examples are included throughout the report. The entire interactive dashboard can be downloaded [here](https://github.com/puhan63/policesentiment/blob/main/Police%20Sentiment%20New%20Dashboard.twbx).

![image](https://github.com/puhan63/policesentiment/blob/7acd3300a6ff364132e853e5134536725bb773b6/Overall%20Sentiment%20Scores.png)

ANALYSIS OF DEMOGRAPHICS

**By location**, sentiment scores peaked in Area_3 and were consistently lowest in the SOUTH region across all racial groups.

**By education**, Respect received the highest sentiment ratings across all education levels, though scores declined as education levels increased.

**By age**, sentiment scores for Respect, Trust, and Listening tended to decrease with age. Respect scores were highest among the middle and older age groups, while Safety scored highest among the youngest group.

**By gender**, males reported higher sentiment scores across all categories compared to females.

**By income**, individuals with higher incomes showed the highest sentiment scores across all categories, followed by those with medium and then low income levels.

![image](https://github.com/puhan63/policesentiment/blob/edf48ba25949d8685753c8406959c4f4fde8050b/Demographic%20Images.png)

PERFORMANCE ANALYSIS

Residents of Chicago’s Areas 3 and 5 consistently reported the highest police sentiment scores over time. These sentiment scores reflect four key dimensions: Safety, Trust, Listen, and Respect.

**Safety** refers to how secure individuals feel in their neighborhoods with respect to crime.

**Listen** measures the extent to which residents believe police listen to and consider community concerns.

**Respect** evaluates whether residents feel they are treated with respect by the police.

**Trust** is a composite measure based on the Listen and Respect indicators.

Across all racial groups—including Asian American, African American, Hispanic, White, and Other—Area 3 received higher ratings. White respondents reported the highest sentiment scores across all areas, while African American respondents reported lower scores overall, with the exception of Area 3.

Educational attainment also played a role in sentiment. Individuals with an advanced degree or higher reported stronger police sentiment in Area 3 than those with some college or a high school education or less. Similarly, respondents with annual household incomes of $100,000 or more expressed more favorable sentiment in Area 3.

Age-based trends were also notable. Respondents aged 55 and older gave higher ratings on Listen, Respect, and Trust, whereas individuals aged 18 to 34 reported higher Safety scores compared to older age groups.

When evaluating the dataset with missing values, the overall trends remained consistent. However, in the analysis of overall sentiment by Education, Trust, and Safety received the highest scores, primarily due to the absence of data for the Listen and Respect category.

