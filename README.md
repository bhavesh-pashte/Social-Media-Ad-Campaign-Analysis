# Social-Media-Ad-Campaign-Analysis

# Source of Dataset:
We received data from a marketing agency company through an acquaintance.

# Dataset Description:
The dataset contains data from the platforms such as Facebook and Instagram Ad Campaigns ran by an agency.
Originally the dataset had 16 columns, after performing feature engineering (segregating data from few columns) there are total 18 columns in the dataset. 
Each column (feature) is described below:
1.	Campaign Name: Describes the names of various campaigns. 
2.	Month: The months in which particular Ad campaign was run.
3.	Ad Name: Describes the names of various advertisements.
4.	Platform: Describes social media platform i.e., Facebook, Instagram.
5.	Reach: It is the measurement of the size of the audience that has seen your ads or campaign content.
6.	Frequency: Frequency is the number of times a user sees ads in your Display or Video campaign over a given time period. 
How it is calculated - Impression/Reach
7.	Impressions: Impressions usually describe how often content appears on a user's screen or feed.
8.	ThruPlays: ThruPlays is a metric in development, which will count the number of times a video is played to completion or at least 15 seconds
9.	CostPerThruPlays: This metric measures the average cost of each ThruPlay.
How it is calculated – Total amount spent on ad/No. of ThruPlays.
10.	Amount Spent (INR): Total amount spent on a specific ad on each platform.
11.	Post Engagement: This metric shows how involved followers are with the content posted on a social media page.
12.	Link Click: Number of clicks on the link.
13.	Clicks (all): The "clicks (all)" metric includes link clicks as well as clicks on other parts of your ad, e.g., someone clicks on your Page's name.
14.	Video Plays at 25%: The number of times your video was played at 25% of its length, including plays that skipped to this point.
15.	Video plays at 50%: The number of times your video was played at 50% of its length, including plays that skipped to this point.
16.	Video plays at 75%: The number of times that your video was played at 75% of its length, including plays that skipped to this point.
17.	Video plays at 100%: The number of times your video was played at 100% of its length, including plays that skipped to this point.
18.	VTR: View-through rate (VTR) measures the number of viewers who watched an entire video ad divided by the number of impressions, or people exposed to the video.

There are total 4 Qualitative Columns, out of which Campaign Name, Month and Ad Name are Nominal & Platform is Binary.
There are total 14 Quantitative Columns, out of which Frequency, CostPerThruPlay and VTR are continuous and rest all are discrete.

# Overview
Performed extensive Exploratory Data Analysis on the Social Media Ad Campaign Dataset to gain valuable insights.

Built WordClouds, Bar Plots and various visualisations to understand the data better and analyse the performance of each Ad campaign.

Implemented Principal Component Analysis (PCA) a dimensionality reduction technique on highly co-related columns to avoid overfitting.

Built a Decision Tree Regression Model with R2 Score of 0.8677 to predict Click Through Rate (CTR).
