# Task_04_Descriptive_Stats
This project explores descriptive statistics for three datasets from the 2024 US presidential election using three different approaches: pure Python, Pandas, and Polars. The goal is to compare these methods, highlight their strengths and quirks, and share the lessons learned throughout the process.
Datasets Analyzed
Facebook Ads: 2024_fb_ads_president_scored_anon.csv
Facebook Posts: 2024_fb_posts_president_scored_anon.csv
Twitter Posts: 2024_tw_posts_president_scored_anon.csv
How did I run analysis
1.	Make sure the datasets (not included here) are in the datasets_period_03_unzipped folder, as described in the assignment.
2.	Running each script for each dataset and methods : 

Pure Python
•	pure_python_2024_fb_ads_president_scored
•	pure_python_stats__fb_posts_president_scored
•	pure_python_stats_2024_tw_posts_president_scored


Pandas
•	Polars_stats_2024_fb_ads_president_scored
•	Polars_stats_2024_fb_posts_president_scored
•	Polars_stats_2024_tw_posts_president_scored

Polars
•	Pandas_stats_2024_fb_ads_president_scored
•	Pandas_stats_2024_fb_posts_president_scored
•	Pandas_stats_2024_tw_posts_president_scored

Each of the script will create the results file specific to the dataset and method used.

Output Files : 
•	Output_python_2024_fb_ads_president_scored_
•	Output_python_2024_fb_posts_president_scored
•	Output_python_2024_tw_posts_president_scored
•	Output_Pandas_fb_ads_pandas_stats
•	Output_Pandas_fb_posts_pandas_stats
•	Output_Pandas_tw_posts_pandas_stats
•	Output_polars_fb_ads_president
•	Output_Polars_fb_posts_stats
•	Output_Polars_tw_posts_stats

Interesting Facts : 
•	Pure Python gave me full control but was more tedious for grouping and pretty output. 
•	Pandas made the process faster and more flexible, especially for groupby and describe(). 
•	Polars surprised me with how quickly it can process big files and its built-in lazy execution, but it required more careful type handling. Overall, I learned the trade-offs between transparency, speed, and ease of use.
