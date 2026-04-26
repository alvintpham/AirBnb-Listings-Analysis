# Paris Airbnb Listings Analysis

## Project Overview
Analyzed a large-scale Airbnb listings dataset with a focus on Paris 
using Python to uncover pricing trends, neighbourhood demand, 
accommodation insights, and host growth patterns over time across 
270,000+ records.

## Objectives
1. Profile and QA the data — Validate data quality, handle encoding 
   issues, convert data types, and identify missing values
2. Prepare for Visualization — Filter, aggregate, and reshape the 
   data for meaningful analysis
3. Visualize and Summarize Findings — Create charts to communicate 
   insights around pricing, accommodation, and host trends over time

## Skills Demonstrated
- Data cleaning and encoding handling using Pandas read_csv
- DateTime conversion and time series resampling using resample
- Data filtering and aggregation using groupby, agg, and query
- Multi-condition filtering and column selection using loc
- Data visualization using Matplotlib and Seaborn
- Exploratory data analysis and QA on large scale datasets
- Dual axis chart creation for comparative time series analysis

## Key Findings
- Paris Airbnb prices were highest in the platform's early years 
  when host supply was limited, averaging significantly higher 
  rates than in later years
- As host volume increased throughout the years, increased market 
  competition drove average nightly prices down
- Both new host registrations and average prices declined sharply 
  during the COVID-19 period, consistent with the broader impact 
  of the pandemic on the short term rental market
- Central Paris neighbourhoods command the highest average nightly 
  prices among all neighbourhoods analyzed
- Larger accommodations consistently correlate with higher nightly 
  rates, suggesting group travel is a strong market segment

## Recommendations
- Hosts looking to maximize revenue should target central Paris 
  neighbourhoods which command the highest average nightly prices
- Larger accommodations consistently yield higher nightly rates, 
  suggesting group travel is a strong and profitable market opportunity
- New hosts entering the market post-COVID face less competition 
  as host growth has stabilized since its 2010 peak, presenting 
  a favorable entry opportunity

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Source
Dataset sourced from Maven Analytics. Download and extract the zip 
file, then place the Listings.csv file in the same folder as the 
notebook before running.
[Maven Analytics](https://maven-datasets.s3.amazonaws.com/Airbnb/Airbnb+Data.zip)
