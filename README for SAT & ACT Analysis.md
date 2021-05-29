# Project 1: SAT & ACT Analysis

## Problem Statement

The new format for the SAT was released in March 2016. College Board wants recommendation where money is best spent to improve **SAT** participation rates for a state of our choice. We are provided with data sets that give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017/18.

With the data interpreted and outside research, we will come to a conclusion for a state of our choice and give recommendations to improve **SAT** participation rate.  

---

## Executive Summary

### Contents:
- 2017 Data Import & Cleaning
- 2018 Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Outside Research
- Conclusions and Recommendations

---

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|sat/act_df_2017/18|The states that are participating in the respective exams| 
|**sat/act_participation_2017/18**|*integer*|sat/act_df_2017/18|The participation rate of each state (in %)| 
|**sat_english_reading_science_2017/18**|*integer*|sat_df_2017/18|The SAT score for the section under Evidence-Based Reading and Writing (200 - 800)| 
|**sat_math_2017/18**|*integer*|sat_df_2017/18|The SAT score for the section under Math (200 - 800)| 
|**sat_finalscore_2017/18**|*integer*|sat_df_2017/18|The total score of SAT exam (400 - 1600)| 
|**act_english_2017/18**|*float*|act_df_2017/18|The ACT score for the section under English (1.00 - 36.00)|
|**act_math_2017/18**|*float*|act_df_2017/18|The ACT score for the section under Math (1.00 - 36.00)|
|**act_reading_2017/18**|*float*|act_df_2017/18|The ACT score for the section under Reading (1.00 - 36.00)|
|**act_science_2017/18**|*float*|act_df_2017/18|The ACT score for the section under Science (1.00 - 36.00)|
|**act_finalscore_2017/18**|*float*|act_df_2017/18|The total average score of ACT exam (1.00 - 36.00)|

---

## Conclusions and Recommendations

We have come to a conclusion that states generally prefer ACT over the SAT with more states prefering to make ACT mandatory over SAT (Much more states with 100% participation in ACT over the SAT). However the SAT participation rate is slowly increasing as it starts to gain popularity.

We also concluded that SAT participation rate is negatively correlated with ACT participation rate and SAT average final score. Hence states with increased SAT participation will likely see lower ACT participation and SAT average final score.

Additional data that will be helpful in our investigations would be current budget from the Government supporting Schools and ratio of State population with Number of schools in state.

The state we will be choosing is Iowa as it has low SAT participation of 3% in 2018 and ACT participation in the state is not mandatory (68% in 2018). It currently has a SAT final score of 1265 in 2018 which is likely to deteorirate as SAT participation rate increases in the future. Some ways to increase the SAT participation rate in Iowa would be to offer free or subsidised cost for taking the SAT and do up a comparison between the SAT and ACT to encourage students that might do better in the SAT to participate.

