# 2025Fall_808_code

The code is for the course project of INST 808: Computational Text Analytics using Python in 2025 Fall. Code for this project was heavily built upon codes used in lab assignments.

### Collect data with Reddit API PRAW
**Code file**: data_collection.ipynb <br />
Input file: None <br />
Output file: datasets/df_airelationships.csv; datasets/df_soulmateai.csv; datasets/df_myboyfriendisai.csv; datasets/df_mygirlfriendisai.csv

### Clean data
**Code file**: data_cleaning.ipynb <br />
**Input file**: datasets/df_airelationships.csv; datasets/df_soulmateai.csv; datasets/df_myboyfriendisai.csv; datasets/df_mygirlfriendisai.csv <br />
**Output file**: datasets/df_all_unique.csv

### Sentiment analysis
**Code file**: sentiment_analysis.ipynb <br />
**Input file**: lexicon/en_liwc.txt; datasets/df_all_unique.csv <br />
**Output file**: None. Output are directly printed in .ipynb

### K means clustering on posts before the GPT-5 release
**Code file**: kmeans_beforeGPT5.ipynb <br />
**Input file**: datasets/df_all_unique.csv <br />
**Output file**: datasets/df_beforeGPT5_clusters.csv

### K means clustering on posts after the GPT-5 release
**Code file**: kmeans_afterGPT5.ipynb <br />
**Input file**: datasets/df_all_unique.csv <br />
**Output file**: datasets/df_afterGPT5_clusters.csv

### Anthropomorphism analysis
**Code file**: anthropomorphism.ipynb <br />
**Input file**: lexicon/en_liwc.txt; lexicon/verwilghen_anthro.txt; datasets/df_all_unique.csv <br />
**Output file**: None. Output are directly printed in .ipynb
