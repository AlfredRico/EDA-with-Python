# EDA-with-Python
**Exploratory data analysis using Python packages NumPy and Pandas, boolean masking and groupby() functions to gain preliminary insight**

  Tiktok's social platform can spark creativity and engulf viewers in inspiration and awe. With today's TikTok population reaching near 2 billion monthly users as of 2026, moderators are tasked, in the face of millions of backlogged reports, with devoloping a predictive model to categorize submitted reports identifying content that needs to be reviewed. At the pace of culture, video content on TikTok can spread like wildfire where discussion-driven topics elicit polarized debate and, if flagged or reported, must be addressed by moderators. This process generates large levels of data that can cannot be assessed in a timely enough manner. 

  This project aims to address this issue by developing a predictive model that can determine whether a video contains a claim or offers an opinion, derive any insight into relationships that may exist between variables such as views, likes, shares, comments and ban status, and implement a successful model that will reduce the backlog of user reports allowing moderators to prioritize them more efficiently.

# For This Part of the Project

## Background
At the eariliest stages of the data analysis I will
  * Build a dataframe for the TikTok dataset
  * Examine data types
  * Gather descriptive statistics
  
## The goal
I will be using the 19,382 rows and 12 columns present in the tiktok_dataset.csv for start of this project, bulding a dataframe for the claims classification data, organizing the claims data for the process of EDA and provide a preliminary assessment of relationships that might exist between variables such as author_ban_status and engagement level (views, shares, likes, comments). 

## Project Environment  
**IDE** - Jupyter Notebook  

Python packages  
**NumPy** used primarily for numerical computation and it's wide range in mathematical functionality.  
**Pandas** was used for data manipulation, data structuring and handling  

**Boolean masking** to filter data with respect to the claim_status  
**Groupby()** function to compile and **agg()** function to perform statistical calculations

## Project Overview
### Key Takeaways  
Approximately 49.654% of data is comprised of opinions and 50.346% are claims. Several factors tend to correlate with content claim status and more specifically whether or not the video contains a claim. Higher engagement metrics including number of views, likes, shares and comments, Discussion-driven engagement or, how successfully the content is generating comments, and Author moderation status, banned or active, each seem to play an identifying factor. The data suggests that claim videos tend to receive higher engagement across the board compared to opinion videos. Claim-based content often sparks debate or controversy, encouraging users to interact. Opinion videos are likely to be less provocative or less likely to trigger widespread discussion.  

### Insights  
Factors correlating with video engagement  
* Video type (claim vs optinion)  
  * Claim videos often receive higher engagement  
* Author status  
  * Videos from banned authors sometimes show higher engagement averages  
* Viewer interaction behavior  
  * Engagement increases when viewers agree, disagree, debate the claim, or share the video
