# EDA-Dataset-Investigation-NoShow-Appointments

# Data Analysis Introduction

This project analyzes a dataset of 100k medical appointments in Brazil, focusing on factors influencing patient attendance. The dataset includes patient characteristics such as scheduled day, neighborhood, enrollment in the Brazilian welfare program, and attendance status.

## Analysis Main Target

- What factors predict if a patient will show up for their appointment?


## Data Wrangling

Load data, check dimensions, duplicates, missing values, and perform essential cleaning.



## Exploratory Data Analysis

Compute statistics and create visualizations to address the primary research question.

### Overall Dataset Overview


## Conclusions

- Patients who showed up were nearly four times as many as those who didn't.
- Gender doesn't significantly affect attendance.
- Babies have a high attendance rate, while older individuals (70+ years old) have a lower attendance rate.
- Neighbourhoods vary in attendance rates.
- Having a scholarship, hypertension, alcoholism, or handicap doesn't show a clear correlation with attendance.
- Receiving an SMS message doesn't significantly impact attendance; in fact, more patients who received SMS messages showed up.

**Limitations:**

- No clear correlation between gender, age, hypertension, scholarship, diabetes, alcoholism, handicap, SMS_received, and showing up.
- Gender results might be inconclusive due to the higher number of female patients.
- The "NoShow" column name can be misleading.
