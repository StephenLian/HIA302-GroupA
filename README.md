# HIA302-GroupA
Team A project for HIA 302

Aim : To identify if holidays or periods of increased travel play a role in the further proliferation of COVID-19 in Malaysia. 

General Objective:
- To perform a descriptive analysis on the latest COVID-19 cases and hospitalisations to provide an overview of daily COVID-19 Cases in Malaysia and analyze possible impacts of holidays on COVID-19 cases from 1st August 2022 till 30th November 2022.  
- Utilizing analysis done for recommendation to improve management and understanding of the current COVID-19 situation. 

Specific Objectives: 
- To describe the trend of reported number of daily COVID-19 cases. 
- To identify the trend percentage for daily COVID-19 cases admitted to hospital among daily COVID-19 cases reported in Malaysia.  
- To identify the trend percentage of daily COVID-19 cases admitted to ICU among reported daily COVID-19 cases.  
- To describe daily COVID-19 cases reported by each state in Malaysia.  

 
Hypothesis 
“The increase in COVID-19 cases nationwide will be reflected accordingly after periods of increased mass gatherings as well as interstate travels during holidays and long weekends.” 

Variable requirements:
Daily Covid-19 Cases
Daily Covid-19 cases admitted to Hospital
Daily Covid-19 cases admitted to ICU
Daily Covid-19 cases by each state

Data Collection ;
Source of data
github - MOH Malaysia
https://github.com/MoH-Malaysia/covid19-public

Based on each specific objective;
a)	Specific Objective 1: Cases_malaysia.csv (cases_new)
b)	Specific Objective 2: Combine 2 datasets: Hosp.csv (admitted_x ) / cases_malaysia.csv (cases_new)
c)	Specific Objective 3: Combine 2 datasets: icu.csv (icu_x) / cases_malaysia.csv (cases_new)
d)	Specific Objective 4: cases_state.csv


Data cleaning = 4 months (1st Aug until 30th Nov ) using Python
1. cases_state = Choylee
2. cases_malaysia = Aiswarya
3. hospital.csv = Dr Lian
4. icu.csv = Dr Dura

For ICU cases, there are 2 data frames which are df_icu_daily1 and df_month
1. df_icu_daily1 = consist of 4 columns and 121 rows
2. The 4 columns are : date (as index), daily cases, icu cases and % ((no. of icu cases/no. of daily cases)*100)
3. The 121 rows is representing the date and there are 121 days included in the desriptive analysis. 
4. df_month is referred to total covid 19 cases reported and admitted to ICU per month (August, September,October and Novmeber 2022)
5. df_month consist of 4 columns and 5 rows.
6. df_month columns are : month (index), ICU cases, Monthly cases and % ((total ICU cases per month/ total reported monthly cases)*100)
7. The 5 rows represent the month which are August, September, October, November and December
  
