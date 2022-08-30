# Capstone-Project
The Australian Women on Labour Force in Covid Times

Report Document Capstone Project
The Scenario
The  coronavirus and the pandemic affected the whole society in several ways. Many articles pointed out some groups that would be more affected than others: young people (online classes and delay in entering the job market), the elderly (health) and women, either by the increase in domestic violence, increase in the workload with domestic work and care with dependents, or loss of incoming or employment. Looking at the Labour Force, how has Covid-19 affected the Australian woman?

● Problem, Goals and Audiences
○ The impact of the Covid-19 on Australian Women
○ To understand the scenario and answer the main question, the goals are finding the resolutions for:
The Gender Gap was increased during the Covid-19 pandemic? 
Which industries were more affected?
In what occupations women are the majority?
Were there any decreases in employment? If so, which gender were more affected?
The unemployment rate increased for which group?
The weekly incoming were affected by Covid? If so, which gender were more affected?
○ The criteria success is identify if the gender gap were large during Covid-19 pandemic

● Data Sources and Definitions in a Data Dictionary
○ All the data is from ABS (Australian Bureau of Statistics) and ATO (Australian Taxation Office)
The following files are cleaning data from Labour Force, Census of Population and Housing, Characteristics of Employment Transitions, Education and Work, Survey of Income and Housing, Gender Indicators, Household Impacts of Covid, Personal Incoming, Work Arrangements, Unpaid Work Survey;

Files:
average_account_superannuation_gender_year_2014_2020.csv
bachelor_degree_gender_2021.csv
bacholer_degree_gender_2021.csv
carers_by_sex.csv
Earnings_cleaned.csv
Employment_population_ratio_2012_2022.csv
Engaged_work_study.csv
field_of_job_2021.csv
industries_gender_2010_2020.csv
Jobseeker Mar 2020 to Mar 2021.csv
non_quali_work_status_gender.csv
not_labour_force_1991_2022.csv
occupation_gender_2010_2020.csv
occupation_gender_year.csv
Participation_rate_2012_2022.csv
reason_not_labour_force.csv
reason_to_left_job_retired.csv
Underemployment_rate_2012_2021.csv
Unemployed_gender.csv
Unpaid_work_2021.csv
unpaid_work.csv
weekly_earning_2020.csv
weekly_earning_contract.csv
weekly_earning_gender.csv
weekly_earning_industry_2019_2021.csv
weekly_earning_industry_2019.csv
weekly_earning_industry_2020.csv
weekly_earning_industry_2021.csv
weekly_earning_industry.csv
weekly_earnings_by type emp.csv
All the columns were extracted to a new table and the cleaning and wrangling data were manipulated on Python (see Jupyter Notebook).
For this project the tools used were:
Excel (extracted and prepared data)
Python (cleaning and formation, imported to SQL postgresql)
SQL (manipulated data, calculations and grouping)
Tableau (connected to SQl database and created dashboard to show the finds)


● Patterns, Trends and Insights
○ Patterns:
With grouping, calculations and filters on SQL; visualisations on Tableau, some patterns were identified:
Gender Gap: women still have less income, participation on Labour force, spent more time taking care of others and housework, are the majority on part-time jobs and work in industries that pay less.
in other hand, the difference on employment in average were round 1%


● At least one predictive model
○ Predictive Model:
What is the future of Women in the Labour Force in Australia? Using Forecast in Tableau is possible to expect equality on participation in the Labour Force in 2032.


● Recommendations
○ Gender Gap
We still have a large group of women working in part-time type of employment, studies pointing the main cause is because women are the primary-care in household arrangements. Even they have higher degree of formal education, they have more interruption in their career to take care of children, illness families or aged care, influencing their longer term incoming and retirement. 
The Covid-19 pandemic had less impact because the flexibility of work for many occupations has become possible. 

○ Recommendations:
Child Care affordable;
Aged care qualified and safe;
Review work pay;

○ Outline any setbacks and make recommendations of any further data required or a new data model to be built (if required).
The source of the data is rich and qualified, however, they had some changing over the years and the format of data is different depending of the year, the model of collecting, processing and delivery. From 2018 is standardised, becoming easy to correlate and making connections between tables.

○ Next steps - What would you do next?
Many articles suggested a larger gap during covid times, which could be possible if more time could be spending analising data. ABS and others statistic researches are still releasing data about Covid, with granulated data and more time, better results can be found. 

