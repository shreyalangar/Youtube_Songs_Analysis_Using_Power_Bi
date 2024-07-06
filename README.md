# Youtube_Songs_Analysis_Using_Power_Bi

**Problem Statement:**

This project intends to conduct a comprehensive analysis of YouTube songs data using Power BI. The analysis aims to uncover trends, preferences, and patterns in the data to aid content creators and stakeholders in optimizing their YouTube song content.

**Problem Objective:**

The goal is to utilize Power BI to create insightful visualizations and reports that provide a deeper understanding of YouTube songs' performance, popularity, and user engagement.

**Dataset Information:**

The songs.csv dataset contains 19345 rows and 13 following columns:

1. video_id: Unique identifier for each YouTube video.
2. channelTitle: Title of the YouTube channel publishing the song.
3. title: Title of the YouTube song video.
4. description: Description provided for the YouTube song video.
5. tags: Tags associated with the YouTube song video.
6. publishedAt: Date and time when the YouTube song video was published.
7. viewCount: Number of views received by the YouTube song video.
8. likeCount: Number of likes received by the YouTube song video.
9. favoriteCount: Number of times the YouTube song video has been marked as a favorite.
10. commentCount: Number of comments posted on the YouTube song video.
11. duration: Duration of the YouTube song video.
12. definition: Video definition or quality (e.g., HD, SD).
13. caption: Availability of captions for the YouTube song video.

**Steps involved:**

1. Data Cleaning and Preparation
2. Exploratory Data Analysis (EDA)
3. Content and Channel Analysis
4. Temporal Trends
5. User Engagement Insights

**Dashboards:**

1. Home Dashboard:
   
![home](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/82d298bf-adfb-45e0-8be2-25a7a252e5ab)

The Home Dashboard provides a high-level summary with key metrics and trends about the data:

- KPIs: Total videos, views, likes, comments, favorites, and average engagement rate.
- Trending Metrics: Recent trends in views, likes, and comments.
- Top Performers: Highlights of top channels and videos.
- Interactive Filter: Options to filter data by channel, video quality, and other relevant parameters.

2. Video Performance Dashboard:

![Video_performance](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/1a05f0fd-e81a-48c6-a312-d5d8dcd90b74)

The Video Performance Dashboard provides detailed insights into how individual videos are performing in terms of views, likes, comments, favorites, and other metrics. This dashboard helps identify top-performing videos, understand trends over time, and uncover factors contributing to video success.

- Top Videos by Key Metrics: Bar charts or tables showcasing top videos based on views, likes, comments, and favorites.
- Performance Trends Over Time: Line charts showing trends for key metrics over time.
- Video Duration Analysis: Histograms or scatter plots analyzing the impact of video duration on performance.
- Video Quality Analysis: Pie charts or bar charts analyzing the distribution of video quality.
- Caption Availability Analysis: Bar charts or pie charts analyzing the impact of captions on video performance.
- Tag Analysis: Word clouds or bar charts showing popular tags and their impact on performance.

3. Engagement Dashboard:

![engagement](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/7a9ca7fa-84f2-45e4-ad46-216ba32a9db1)

The Engagement Dashboard provides insights into how users interact with your YouTube videos. It focuses on various engagement metrics like views, likes, comments, shares, and favorites. This dashboard helps you understand which videos resonate the most with your audience and why.

- Engagement Overtime: A line chart showing the trend of engagement rate over time. 
- Video Duration Analysis: Histograms or scatter plots analyzing the impact of video duration on engagement rate.
- Top Songs by Engagement Rate: Bar charts or tables showcasing top songs based on engagement rate.
- Distribution of Metrics: Pie charts analyzing the distribution of engagement metrics.
- Tag Analysis: Line charts showing impact of tags on engagement rate.

**Inferences:**

1. Which song video has the highest view counts?
- Vaaste Song: Dhvani Bhanushali, Tanishk Bagchi | Nikhil D | Bhushan Kumar | Radhika Rao, Vinay Sapru has the highest view counts.
  - ![image](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/022b89c7-b752-4e4e-a6dd-917dc6df1706)

2. What is the trend in engagement (likes, comments, favorites) over time?
- From the engagement dashboard, we can see a significant increase in the engagement rate over the years.
  - ![image](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/459ed2f7-c5df-48d9-a559-ab5b1416bf7b)

3. Are there specific tags or keywords that consistently correlate with higher viewer engagement?
- Tags like 'tseries', 'hindi songs' and 'bollywood songs' correlate highly with the viewer engagement rate.
  - ![image](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/bd073df3-ab7b-4891-ba52-5d5ab05c2bad)

4. Is there a correlation between video duration and viewer engagement (views, likes, comments)?
- The songs having short duration have higher viewer engagement as compared to songs having long duration.
  - ![image](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/21423a18-3609-4285-954e-38b89fe73949)

5. Which songs have the highest engagement rate (engagements per view)?
- The songs having highest engagement rate are: 
- De De Pyaar De - Official Trailer (Russian) | Ajay Devgn, Tabu, Rakul Preet Singh | Akiv Ali
- Tere Mere Beech Mein Song | Babul Supriyo | Lal Sarkar
- Jubin Nautiyal: Aise Kaise (Lyrical) | Rohanpreet Singh, Rana Sotal | Bhushan Kumar
  - ![image](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/7d15c33d-6644-4b24-bb63-0ff33720aac0)

6. Are there seasonal trends in song popularity or viewer engagement?
- There doesn't appear to be any seasonal trends in viewer engagement.

7. How does video quality (e.g., HD vs. SD) impact viewer engagement?
- 'HD' quality videos show much higher viewer engagement as compared to 'SD' quality videos.
  - ![image](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/51693624-e3fa-4981-871a-85792fa9ab98)
  - ![image](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/f6d5aa4d-54aa-4516-8c19-f3b918f16e2a)

8. What were the top songs in the past year (2023) by likes?
- Top songs in 2023 by likes were:
- Ram Siya Ram (Hindi) Adipurush | Prabhas | Sachet-Parampara, Manoj Muntashir | Om Raut | Bhushan K
- Achha Sila Diya |Jaani & B Praak Feat. Nora Fatehi & Rajkummar Rao | Nikhil-Vinay,Yogesh | Bhushan K
- Jai Shri Ram (Hindi) Adipurush | Prabhas | Ajay-Atul, Manoj Muntashir Shukla | Om Raut | Bhushan K
  - ![image](https://github.com/shreyalangar/Youtube_Songs_Analysis_Using_Power_Bi/assets/73985138/e0ea46e2-c089-4636-98c3-2fb8817d24fd)




