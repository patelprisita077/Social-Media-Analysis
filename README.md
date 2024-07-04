# Social-Media-Analysis
Overview:
This project analyzes the relationship between social media usage patterns and emotional well-being using a comprehensive dataset. The goal is to evaluate how different social media metrics influence users' emotional states and to build predictive models to classify the dominant emotion based on these metrics.

Dataset:
The dataset contains various social media metrics and the dominant emotional state of users, with the following columns:

User_ID: Unique identifier for each user.
Age: Age of the user in years.
Gender: Gender identity of the user (Female, Male, Non-binary).
Platform: The social media platform used by the user (e.g., Instagram, Twitter, Facebook, LinkedIn, Snapchat, WhatsApp, Telegram).
Daily_Usage_Time (minutes): Total minutes spent daily on the specified platform.
Posts_Per_Day: Number of posts made per day.
Likes_Received_Per_Day: Number of likes received per day.
Comments_Received_Per_Day: Number of comments received per day.
Messages_Sent_Per_Day: Number of messages sent per day.
Dominant_Emotion: The dominant emotional state of the user during the day (e.g., Happiness, Sadness, Anger, Anxiety, Boredom, Neutral).
Insights:

Age Distribution: Majority of users are aged between 21 and 35, with the highest counts in the age group of 27 and 28.
Platform Distribution: Instagram is the most used platform, followed by Twitter and Facebook.
Instagram: 250 users
Twitter: 200 users
Facebook: 190 users
LinkedIn: 120 users
WhatsApp: 80 users
Telegram: 80 users
Snapchat: 80 users
Daily Usage Time: Ranges from 40 to 200 minutes, with most users spending 60 to 90 minutes daily. The average usage time is 95 minutes.
Posts Per Day: Minimum of 1 post and a maximum of 8 posts per day.
Emotions Distribution:
Happiness: 20.1%
Anger: 13.2%
Neutral: 19.9%
Anxiety: 16.9%
Boredom: 14.1%
Sadness: 15.8%
Gender vs. Platform Usage:
Instagram is most used by females, while Facebook is the least.
Twitter is most used by males, followed by Instagram. WhatsApp is the least used.
Facebook is most used by non-binary users.
Correlations:
Daily usage time is highly correlated with likes received per day.
Age is highly correlated with comments received per day.
Model Performance:

Random Forest Classifier: Accuracy: 99%

The model performs exceptionally well with nearly perfect precision, recall, and f1-scores for most classes, indicating its high effectiveness at predicting the dominant emotion.
XGBoost Classifier: Accuracy: 97%

This model also performs very well, with high precision, recall, and f1-scores for most classes. It shows slightly less precision in predicting 'Anxiety' compared to other emotions.
Decision Tree Classifier: Accuracy: 97%

Similar to the Random Forest Classifier, this model achieves high precision, recall, and f1-scores, indicating its effectiveness in predicting the dominant emotion.
Conclusion:
This project successfully demonstrates the ability to analyze social media usage patterns and predict users' emotional states using advanced machine learning models. The insights gained can be instrumental in understanding the impact of social media on emotional well-being and developing strategies for healthier social media usage.
Key Insights:

Utilized advanced data analysis techniques to examine social media usage patterns for 1,000 users, revealing that 60% of users are aged between 21 and 35, with peak usage at ages 27 and 28.
Applied data visualization skills to identify Instagram as the most popular platform with 250 users, compared to LinkedIn and Telegram with the lowest usage at 80 users each.
Demonstrated data interpretation skills by finding a high correlation (0.94) between age and comments received per day, providing valuable insights into user engagement patterns.
Leveraged machine learning models, including Random Forest and XGBoost classifiers, to predict dominant emotions, finding 'Happiness' as the most common emotion (20.1%), followed by 'Neutral' (19.9%) and 'Anxiety' (16.9%).
