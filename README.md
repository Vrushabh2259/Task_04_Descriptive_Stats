# Task_04_Descriptive_Stats
This project explores descriptive statistics for three datasets from the 2024 US presidential election using three different approaches: pure Python, Pandas, and Polars. The goal is to compare these methods, highlight their strengths and quirks, and share the lessons learned throughout the process.
Datasets Analyzed
1.	Facebook Ads: 2024_fb_ads_president_scored_anon.csv
2.	Facebook Posts: 2024_fb_posts_president_scored_anon.csv
3.	Twitter Posts: 2024_tw_posts_president_scored_anon.csv
How did I run analysis
1.	Make sure the datasets (not included here) are in the datasets_period_03_unzipped folder, as described in the assignment.
2.	Running each script for each dataset and methods : 

Pure Python :
1.	pure_python_2024_fb_ads_president_scored
2.	pure_python_stats__fb_posts_president_scored
3.	pure_python_stats_2024_tw_posts_president_scored

Pandas 
1.	Polars_stats_2024_fb_ads_president_scored
2.	Polars_stats_2024_fb_posts_president_scored
3.	Polars_stats_2024_tw_posts_president_scored

Polars
1.	 Pandas_stats_2024_fb_ads_president_scored
2.	Pandas_stats_2024_fb_posts_president_scored
3.	Pandas_stats_2024_tw_posts_president_scored

Each of the script will create the results file specific to the dataset and method used.

Output Files : 
1.	Output_python_2024_fb_ads_president_scored_
2.	Output_python_2024_fb_posts_president_scored
3.	Output_python_2024_tw_posts_president_scored
4.	Output_Pandas_fb_ads_pandas_stats
5.	Output_Pandas_fb_posts_pandas_stats
6.	Output_Pandas_tw_posts_pandas_stats
7.	Output_polars_fb_ads_president
8.	Output_Polars_fb_posts_stats
9.	Output_Polars_tw_posts_stats

Interesting Facts : 
1.	Pure Python gave me full control but was more tedious for grouping and pretty output. 
2.	Pandas made the process faster and more flexible, especially for groupby and describe(). 
3.	Polars surprised me with how quickly it can process big files and its built-in lazy execution, but it required more careful type handling. Overall, I learned the trade-offs between transparency, speed, and ease of use.




