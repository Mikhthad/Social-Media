# Social-Media
![image](https://github.com/user-attachments/assets/f5efa8ec-0a62-4c0b-a7f9-dab2c555940f)

## Overview
This project focuses on analyzing time-wasting behaviors on social media platforms using user data. The dataset includes variables such as age, income, video engagement, addiction levels, and productivity loss. The goal is to identify patterns in social media usage and provide insights into user behavior, addiction, and its effects on productivity.
## Dataset
The dataset consists of the following key features:

UserID: Unique identifier assigned to each user.
Age: The user's age.
Gender: The user's gender (e.g., male, female, non-binary).
Location: Geographic location of the user.
Income: The user's income level.
Debt: Amount of debt the user has.
Owns Property: Indicates whether the user owns property.
Profession: The user's occupation or job.
Demographics: Statistical data about the user (e.g., age, gender, income).
Platform: The platform the user is using (e.g., website, mobile app).
Total Time Spent: The total time the user spends on the platform.
Number of Sessions: The number of times the user has logged into the platform.
Video ID: Unique identifier for a video.
Video Category: The category or genre of the video.
Video Length: Duration of the video.
Engagement: User interaction with the video (e.g., likes, comments, shares).
Importance Score: A score indicating how important the video is to the user.
Time Spent On Video: The amount of time the user spends watching a video.
Number of Videos Watched: The total number of videos watched by the user.
Scroll Rate: The rate at which the user scrolls through content.
Frequency: How often the user engages with the platform.
Productivity Loss: The impact of platform usage on the user's productivity.
Satisfaction: The user's satisfaction level with the platform or content.
Watch Reason: The reason why the user is watching a video (e.g., entertainment, education).
Device Type: The type of device the user is using (e.g., smartphone, tablet, desktop).
OS: The operating system of the user's device (e.g., iOS, Android, Windows).
Watch Time: The time of day when the user watches videos.
Self Control: The user's ability to control their usage of the platform.
Addiction Level: The user's level of dependency on the platform.
Current Activity: What the user is doing while watching the video.
Connection Type: The type of internet connection the user has (e.g., Wi-Fi, cellular).
## Information of the dataset
Columns = 31
Rows = 1000
data types
bool = 2
integer = 16
object = 13
No null vaues
Cleaned data
## Technologies Used
Python
Pandas for data manipulation
Matplotlib and Seaborn for data visualization
Jupyter Notebook for analysis and reporting.
## Key Analyses
The analysis includes the following visualizations and insights:

1. Correlation Heatmap: Visualizes the relationships between such as int64','float32.
2. Pie PLot:
    Distribution of Addiction Levels
    Total Time Spend by Profession
    Total Time Spent by Platform
    Average User Satisfaction by Video Category
4. Bar Plot:
    Location of Users
    Age Distribution of Users
    Profession of users
    Most Frequently Visited Social Media Platforms
    Avg Addiction Level Across different Platform
    Total Time Spent on Video Categories by Platform
    Avg Addiction Level by Frequency of Use
    Self Control and Its Impact on User Satisfaction   
5. Line Plot
    Impact of Profession and Watch Reason on Social Media Addiction Levels
    Trend of Social Media Addiction Level Based on Watch Time Across Platforms
    Avg Time Spent by Frequency of Use
6. Scatter Plot
    Relationship Between Self Control and Addiction Level
## Suggestions Based on Analysis:
Encourage Time Management Features: Social media platforms could introduce time limit reminders or personalized usage summaries, especially for users with higher Addiction Levels and lower Self-Control.

Promote Productive Content: Encourage users to engage with content that offers value, such as educational or professional videos, by boosting its visibility.

Limit Engagement for Highly Addictive Content: Introduce features that reduce autoplay for content categories that show high engagement but lead to productivity loss (e.g., entertainment).

User Satisfaction Boosters: Platforms should promote content types and features that enhance Satisfaction (e.g., personalized video recommendations based on user preferences).

Create User Profiles for Behavioral Nudges: Tailor notifications or recommendations based on user behavior (e.g., total time spent, number of sessions) to help users improve their platform habits.

Monitor Peak Time Usage: Platforms can provide feedback to users on when they tend to overuse, especially during off-peak hours (e.g., late at night).



