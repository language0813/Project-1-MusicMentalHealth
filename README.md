# Project 1

For Project 1, our team was required to find and analyze a dataset of our choice. We chose to explore Mental Health and Music. 

## Context

Music therapy (MT) involves using music to enhance an individual’s stress levels, mood, and overall mental well-being. It is an evidence-based practice known for stimulating the release of "happy" hormones like oxytocin.

MT utilizes a diverse array of music genres, with the specific approach varying across different organizations.

The MxMH dataset is designed to explore potential correlations between a person’s music preferences and their self-reported mental health. 736 respondents answered questions focused on musical preferences, listening habits and mental health.

Ultimately, the goal is to either refine the application of MT or offer intriguing insights into the relationship between music and mental health.



## Analysis: The Impact of Music on Mental Health and Implications for Music Therapy

The MxMH dataset explores the relationship between music preferences, streaming habits, and self-reported mental health conditions such as Depression, Anxiety, Insomnia, and OCD. The findings from the data can contribute to the understanding of how music affects mental health and the potential application of Music Therapy (MT).

### 1. Streaming Service Usage and Mental Health
**Question:** Is there a correlation between the primary streaming service used and mental health indicators (anxiety, depression, insomnia, OCD)?

**Analysis:** Compare mental health scores across different streaming services (e.g., Spotify, Pandora, YouTube Music).

![Screenshot 2024-08-13 at 1 20 24 PM](https://github.com/user-attachments/assets/240410c1-310f-45c6-bd3a-ee74ad7920de)


+ Different streaming services are associated with varying levels of mental health conditions.
+ Pandora users generally report lower levels of Depression, Anxiety, Insomnia, and OCD, suggesting a potentially less negative or more positive impact of this service on mental health.
+ Spotify and Apple Music users report higher levels of these conditions, which could indicate that the content or usage patterns associated with these services are linked to higher mental health symptoms.

**Implication:** The differences between streaming services could be related to user demographics, the type of music content provided, or the specific ways in which people engage with these platforms. This insight is valuable for MT practitioners when recommending music platforms or content.

###  2. Favorite Genre and Mental Health
**Question:** Does the favorite genre of music have an impact on mental health conditions?

**Analysis:** Compare mental health scores for different favorite genres.

![Screenshot 2024-08-13 at 1 23 13 PM](https://github.com/user-attachments/assets/981a576f-17ed-4e4c-8670-ba5f6d75dfd3)


+ Prior to analysis, the dataset was cleaned, sorted by genre and the mean for each mental health condition was calculated. 
+ As observed in the bar charts, the genre of music listened to showed correlations with mental health outcomes.
+ Overall, Lofi tends to be associated with higher levels across all four metrics while Gospel appears to be consistently associated with lower levels of anxiety, depression, and OCD.

**Implication:** Certain genres might exacerbate or alleviate mental health conditions. MT practitioners could leverage these insights to tailor music therapy interventions more effectively. For instance, avoiding certain genres or emphasizing others could potentially improve mental health outcomes.

### 3. Music Effects on Mental Health Conditions
**Question:** What are the self-reported effects of music on various mental health conditions (anxiety, depression, insomnia, OCD)?

**Analysis:** Analyze the 'Music effects' column in relation to mental health scores.

![Screenshot 2024-08-13 at 1 04 14 PM](https://github.com/user-attachments/assets/e1f091b7-4e9d-4872-b2c1-32f32e960cf2)

+ The dataset reveals diverse effects of music on individuals with varying levels of Depression, Anxiety, Insomnia, and OCD.
+ A significant number of individuals report that music improves their condition, particularly for Anxiety and Depression. However, a notable portion also reports no effect or even a worsening of symptoms.


**Implication:** Music therapy should be personalized, as the effects of music on mental health are not uniform. While some individuals might find music therapeutic, others might experience no benefit or even a deterioration in their condition. Understanding a patient’s specific reactions to music is crucial for effective MT interventions.

### 4. Hours Spent on Music and Mental Health
**Question:** How does the number of hours spent listening to music per day affect mental health?

**Analysis:** Analyze the relationship between hours per day and mental health scores.

![Screenshot 2024-08-13 at 12 59 07 PM](https://github.com/user-attachments/assets/df9ad171-3907-45df-8204-238af769531b)

+ The bar chart shows the distribution of hours spent listening to music per day for each respondent. Most respondents spent around 2 to 5 hours per day listening to music.
+ For the initial analysis, the data were grouped into 5 intervals based on hours spent listening to music per day, and the average self-reported level of mental health issues for each group was calculated, as shown in the table. Based on the data in the table, there is no obvious trend between the hours spent listening to music per day and the level of each mental health issue. However, note that the 21 to 24 hours per day group has the lowest level of each mental issue compared to the other groups.

![Screenshot 2024-08-13 at 1 31 02 PM](https://github.com/user-attachments/assets/f311bfc3-4668-467d-a602-8ee1ce0263b9)

+ To further examine the relationships, scatter plots were created with hours per day versus each mental health issue, and a linear regression model was applied to each plot. The r value and r-squared value were then calculated for each relationship.
+ As shown in the four plots, the data are dispersed and the line of best fit is mostly flat in each relationship, indicating there is no obvious correlation.
+ The r values for all the relationships are lower than 0.14, indicating either no correlation or a very weak correlation.
+ The r-squared values for all the relationships are lower than 0.02, suggesting that only 2% of the data can be explained by the hours spent listening to music per day.

**Implication:** Even though there are some positive correlations, the low r values and r-squared values indicate that there is no significant relationship between the hours spent listening to music per day and the level of the four types of mental health issues.

### Conclusion:
The analysis of the MxMH dataset suggests that music has a complex and multifaceted impact on mental health. While certain types of music or streaming services may correlate with higher mental health symptoms, others might offer therapeutic benefits. The key takeaway for Music Therapy is the need for personalized approaches—considering the type of music, the amount of time spent listening, and individual patient responses to different genres and platforms. This personalized approach could maximize the therapeutic benefits of music, helping individuals with mental health conditions more effectively.



 ## Synopsis of Process

To tackle this challenge we...

1. Read and decoded the requirements of the project.
2. Researched current questions/problems in the Data Analystics Field and to find possible data sources to address the problem.
3. Brainstormed possible structures needed to accomplish the goals of the challenge.
4. Looked back at Bootcamp class activites to find code to accomplish processes.
5. Researched the resources listed below to find additional, or more elegant, code.
6. Cleaned, merged and tested scripts.
7. Used observations to create an analysis.
8. Outlined and created presentation.
10. Presented findings.
11. Updated analysis and presentation based on feedback.


## Resources

+ https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results/data?select=mxmh_survey_results.csv
+ Previous Bootcamp Challenges
+ PowerPoint
+ ChatGPT



## Table of Contents
+ main.ipynb (Code used to clean and analyze the dataset)
+ Music and Mental Health.pdf (Slide Deck used for presentation)
+ Data folder (Music and Mental Health Survey dataset)
+ Project 1 (Original Project Requirements)
+ README.md
