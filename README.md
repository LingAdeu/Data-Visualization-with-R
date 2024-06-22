![header](header.png)

# Global Suicide Rate Analysis

## About
This project explores the trends and patterns of global suicide rates using a dataset from the World Health Organization (WHO). The analysis focuses on understanding whether the global suicide rate has fallen over the past several decades, examining trends by gender, age groups, and countries. The goal is to raise awareness about the critical issue of suicide and its impact on society. 

## Dataset
The dataset used in this analysis is sourced from [Kaggle](https://www.kaggle.com/datasets/szamil/who-suicide-statistics) and includes the following features:
- `country`: Names of 118 countries
- `year`: Time unit ranging from 1979 to 2016 (37 years)
- `sex`: Gender of the individual (male or female)
- `age`: Age groups (5–14 years, 15–24 years, 25–34 years, 35–54 years, 55–74 years, 75+ years)
- `suicides_no`: Number of suicide cases
- `population`: Total population in the country
The dataset contains 43,776 observations, of which 36,060 are complete and used for analysis after cleaning.

## Key Findings
Based on the analysis, my findings can be summed up into the following points:
- **Trend Analysis**:
    - Suicide rates increased globally from 1979 to 2001, followed by a significant decrease from 2014 to 2016.
    - Male suicide rates are higher than female, with males showing steeper trends.
- **Country-Specific Analysis**:
    - Hungary, Lithuania, Russian Federation, and Latvia have the highest suicide rates.
    - These countries show significantly higher rates compared to the global average.
- **Age Group Analysis**:
    - Older age groups have higher suicide rates.
    - The rate increases notably from the youngest age group (5–14 years) to older age groups.
- **Within-Country Changes**:
    - Most countries show a decline in suicide rates from 2000 to 2015.
    - The Republic of Korea is an exception, showing an increase in suicide rates during this period.
    - Russian Federation, Hungary, and Latvia show the largest decreases in suicide rates.

## Folder Organization
    .
    ├── README.md                           <- The top-level README for using this project.
    ├── data
    │   └── who_suicide_statistics.csv      <- Dataset
    └── notebook
        ├── Datviz_Suicide_Cases.Rmd        <- Flex Dashboard for data visualization (dashboard format)
        └── Suicide_Rate_Script.qmd         <- Quarto notebook for the analysis


## Usage
To replicate my analysis or explore the data further, kindly follow the following steps:
1. Clone this repository to your local machine.
```bash
git clone https://github.com/yourusername/global-suicide-rate-analysis.git
```
2. Ensure that all necessary dependencies are installed. These can be done by running the following script on the Interactive Development Environment (IDE, e.g., RStudio or Visual Studio Code).

```r
install.packages(c("tidyverse", "readr", "dplyr", "ggplot2"))
```
3. Run file Suicide_Rate_Script.qmd in notebook folder to reproduce the analysis.

## Feedback
If you have suggestions for improvements, feel free to contact me here:

<a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:januartoadelia@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>