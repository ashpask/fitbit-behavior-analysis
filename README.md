FitBit User Behavior Analysis

Google Data Analytics Professional Certificate Capstone Project


Background

I chose this dataset because I own a Garmin watch and find the data that fitness trackers collect genuinely fascinating. These devices reveal how people actually live, and I wanted to explore what the numbers say about real behavior. I picked this over the provided case studies because I wanted to work with something I actually care about.
This project analyzes FitBit tracker data from 33 users collected over April and May of 2016 to find patterns in daily activity, sleep quality, and peak movement times.

 
Dataset

Source: FitBit Fitness Tracker Data on Kaggle, made available by Mobius.
I used three files: dailyActivity_merged.csv, sleepDay_merged.csv, and hourlySteps_merged.csv.


Process
I followed the six phase framework taught in the Google Data Analytics course: Ask, Prepare, Process, Analyze, Share, and Act. I defined three business questions, cleaned the data in Excel by removing duplicates and formatting dates, ran averages and a correlation analysis, built a dashboard with three charts, and wrote recommendations based on what I found.


Key Findings
1. Users spend 81% of their day sedentary and average only 7,638 daily steps, which is well below the recommended 10,000 daily steps. With only 21 minutes of vigorous activity a day, there is a lot of room for improvement for these users.
2. There is no meaningful correlation between sleep and steps. Users average 7 hours of sleep but steps vary. Users spend 39 minutes awake in bed per night, suggesting poor sleep quality may stem from pre-sleep routines like phone use.
3. 12:00 am - 2:00 pm and 5:00 pm to 7:00 pm are the most activity times. This may be due to lunch walks and after-work activities.


Recommendations
1. Wellness companies and fitness app developers should send movement reminders during the most sedentary hours of the day, roughly 9am to 11am and 1pm to 4pm.
2. A pre-sleep wind-down feature that discourages phone use about 40 minutes before bed could help close the gap between time in bed and actual sleep.
3. Push notifications and fitness challenges should be timed around noon and early evening, when users are already most likely to move.


Limitations

The sample size of 33 users over two months limits how broadly these findings can be applied. The sleep and steps correlation was calculated using user level averages rather than day matched records because of how the dataset was structured. The data is also from 2016, so behavior around fitness trackers has likely shifted since then. The findings of this study are also limited to the technologies available at the time of data collection. 


Tools

Microsoft Excel. Data cleaning, pivot tables, AVERAGEIF, CORREL, VLOOKUP, and chart creation.
