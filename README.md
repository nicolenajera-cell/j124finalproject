# Evaluating Unintentional Overdose Death Rates in San Francisco since 2020
Heres a link to my Google Sheet: (https://docs.google.com/spreadsheets/d/1MFw5_SIysLEwY068_xSk1wgg_chUAOc8EOsivsKmlO4/edit?usp=sharing)

Heres a link to my original datasource: (https://data.sfgov.org/Health-and-Social-Services/Preliminary-Unintentional-Drug-Overdose-Deaths/jxrr-bmra/about_data)
## Data Acquisition and Potential Challenges
### Overview: 
- Data was found through DataSF 
- The dataset being used is the Unintentional Drug Overdose Death Rate by Race/Ethnicity dataset, the official open data portal for the City and County of San Francisco
- The dataset is maintained and managed by the San Francisco Department of Public Health using records from the California Electronic Death Registration System 

### Evaluating the Data’s Validity:
- The dataset is generally accurate and trustworthy because it comes from government agencies that collect mortality data as part of public health responsibilities rather than for advocacy or commercial purposes
- The Department of Public Health has an interest in monitoring overdose deaths to guide prevention efforts and inform policy decisions

### Potential Challenge:
- One challenge is that the dataset only includes unintentional overdose deaths occurring in San Francisco. It does not include intentional overdoses or nonfatal overdoses 
- Another limitation could be that racial groups with very small numbers of deaths are placed in a separate category called “All races” in order to protect privacy, meaning some communities may be underrepresented in the published data

## Data Analysis
### Main Findings:
<img width="897" height="178" alt="Screenshot 2026-07-06 at 2 23 21 PM" src="https://github.com/user-attachments/assets/e77e221b-9039-401e-8334-95e0778b89de" />

Table 1: Raw counts of overdose deaths over time among different racial and ethnic groups

- Rows: year, sort by year
- Columns: race_ethnicity, sort by race_ethnicity
- Values: overdose_death_count, show as Default
- The raw counts show that White residents accounted for the largest number of reported overdose deaths (1,416), followed by Black residents (960)

<img width="340" height="157" alt="Screenshot 2026-07-06 at 6 06 47 PM" src="https://github.com/user-attachments/assets/f0a80d32-08fe-4979-bc96-baac7fd8aaea" />

Table 2: Average of annual overdose death rates across racial and ethnic groups 

- Rows: race_ethnicity, sort by AVERAGE of overdose_death_rate
- Values: overdose_death_rate, show as Default 
- This table compares the average annual overdose death rate per 100,000 residents across racial and ethnic groups in San Francisco from 2020 to 2024. Unlike the raw counts in Table 1, these rates account for differences in population size
- The average rates show that Black/African American experienced the highest average overdose death rate, while Asian residents had the lowest

## Data Visualizations 
<img width="606" height="377" alt="Screenshot 2026-07-06 at 3 32 45 PM" src="https://github.com/user-attachments/assets/127e011a-7bbc-4c41-9425-2bf7e4d0b46c" />

This first visualization I created was a line chart displaying the overdose deaths for each racial and ethnic group by year.This visualization illustrates how overdose death counts changed over time across different racial and ethnic groups. This visualization highlights the differences in the impact of the overdose crisis on different racial groups in San Francisco. The findings from this chart show that the raw counts of overdose deaths dislpay White residents as experiencing the highest unintentional overdose deaths

<img width="606" height="377" alt="Screenshot 2026-07-06 at 3 35 09 PM" src="https://github.com/user-attachments/assets/cb453889-982d-465f-bc22-f428967d9092" />

This second visualizaion I created was a horizontal bar chart that compares the average overdose death rate for each racial and ethnic group. By comparing the average overdose death rates, it allows us to notice disparities among racial and ethnic groups while accounting for differences in population size. The findings from this graph show that Black residents experienced a drastically higher average overdose death rate than any other race. It also shows that Asian residents experienced the lowest average overdose death rate in the chart.

## Ethical Concerns and Summary
One of the limitations to consider with this dataset are that there are disparities described that cannot be explained by the data itself. The dataset displays the differences in overdose death rates between racial and ethnic groups but these differences should not be interpreted as being caused by race, but rather may reflect broader social factors such as discrimination and inequality.

Another concern is about privacy and representation. This dataset suppresses very small numbers to protect the privacy of individuals, meaning some communities may not appear in every year of the data. This means that these missing values should not be mistaken as an absence of a certain racial or ethnic group from the data.

This would make a worthwhile data journalism story because it combines public records, accountability reporting, and community impact. By analyzing long-term trends in overdose mortality data and also adding expert and community perspectives, this story can help readers better understand the prevalence of overdose mortality disparities in San Francisco and identify patterns that deserve attention. For this project, the final story would work best as an interactive data-driven article that includes written reporting, visualizations, and interviews. Reviewing reports from the San Francisco Department of Public Health, the California Department of Public Health, and further research could also help explain broader trends that are not visible in the dataset alone. 
