# canada-gender-wage-gap-analysis
Analysis of the gender wage gap among full-time employees in Canada using Statistics Canada data (2024–2026)

## Question
When I explored Statistics Canada wage data I noticed that women's 
wages were growing at a faster rate than men's, but the actual dollar 
difference in average weekly wages between men and women stayed more 
or less the same over the 3 year period. This project investigates 
whether the gender wage gap among full-time employees in Canada is 
actually closing despite women's faster wage growth.
## Data Source
The data came from Statistics Canada — specifically the table 'Average usual hours and wages by selected characteristics, monthly, unadjusted for seasonality' (Table 14-10-0320-02). It measures average weekly wages for full-time employees across various characteristics including gender, age, union status, and occupation type, covering March 2024 to March 2026
## Tools Used
Excel (Power Query for data cleaning, charts for visualization)

## Process
1. Explored the Statistics Canada website to find a dataset 
   that sparked a question worth investigating
2. Downloaded the CSV file for average weekly wages by 
   selected characteristics
3. Opened the file in Excel and cleaned the data using 
   Power Query — removed metadata rows, promoted headers, 
   and confirmed correct data types
4. Added a calculated row showing the dollar difference 
   between Men+ and Women+ wages for each year
5. Created a clustered column chart comparing Men+ and 
   Women+ wages across 2024, 2025, and 2026
6. Created a line chart showing the wage trend over time 
   for both groups

## Key Findings
- Women+ wages grew at approximately 9.1% over the two year 
  period compared to 7.2% for Men+ — about 2 percentage 
  points faster
- Despite this faster growth rate, the dollar gap barely 
  changed — shrinking by only $6.42 over two years 
  (from $254.62 to $248.20)
- The gap actually widened from 2024 to 2025 before 
  narrowing in 2025 to 2026, suggesting the closing 
  may be accelerating recently
- Women started from a significantly lower wage base 
  ($1,318 vs $1,573 in March 2024), which is why faster 
  percentage growth hasn't closed the dollar gap meaningfully
  
## Charts
<img width="482" height="289" alt="image" src="https://github.com/user-attachments/assets/eedabcbd-5d19-4aca-ac36-1dd96a219660" />
<img width="484" height="293" alt="image" src="https://github.com/user-attachments/assets/540c8b6a-ac7e-4249-9f1c-b4459d506a90" />

## How to Use This Repo
- Start by reading this README to understand the question, 
  process and findings behind the analysis
- Open the .xlsx file in Excel to explore the cleaned data 
  and interact with the charts
- Chart screenshots are also available in the repo if you 
  want to view the visualizations without opening Excel

  ## Limitations
  - Only three data points (March 2024–2026) which is enough 
  to identify a pattern but not enough to confirm a long 
  term trend
  - Data covers Canada as a whole — provincial or regional 
  differences are not captured
  - The analysis shows the gap exists and is not closing 
  quickly but cannot explain the underlying reasons why






