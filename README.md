# The Effect of Tone and Content-Type on Brand Social Media Interactions
## Overview
Social media is a powerful tool for brands to communicate with their customers, promote their products, and build their reputation. However, not all social media posts are equally effective in generating engagement from the audience. The tone and content type of a post can influence how the audience reacts to it, and thus affect the brand’s social media performance.

This analysis aims to investigate the relationship between the tone and content type of social media posts and the level of engagement they generate. The analysis will focus on three types of tones: positive, neutral, and negative, and the various types of content available in the dataset.

## Outcomes
This project has helped me to understand how different tones and content types can affect the engagement of social media posts. By analyzing the data, I was able to identify the best practices and strategies for creating effective and engaging social media content for playcom  and audiences. This project has also improved my skills in data analysis, visualization, and communication, as well as my knowledge of social media marketing and branding.

## Methodology
### Data Preparation
The data for this analysis consists of a sample of 8,529 posts from Twitter (now X), with 147 variables. I performed the following steps to prepare the data for analysis:

I checked the shape and the missing values of the data. I found that some columns had null values, which I imputed based on the context of the data. For instance, the linked_post column had missing values for posts that were not linked to any other content.
I standardized the values in the post column by converting them to lowercase, removing emojis, and trimming white spaces. This improved the readability of the posts. I also removed special characters such as commas and percentages from the numeric columns. For example, 1,467 became 1467 and 0.087% became 0.087.
I corrected the data types of some columns, such as Impressions, Likes, and Click-Through Rate, which were initially objects. I converted them to integers and floats as appropriate.
I created new variables to facilitate the analysis and answer the research questions. For example, I created the Tone column Using the SentimentIntensityAnalyzer of python to indicate if the post had a positive, neutral, or negative tone. I also created the Contains Hashtags - checking if a post contains '#', Mention Someone - checking if a post contains '@', Contains Action Words - checking if a post contains words like Share, Click, Comment and Like, Contains Question - checking if the post contains '?', Post Lengths - counting the characters in a post, and Linked to Other Contents columns - checking if the posts contains a link to other posts or contents - to capture different aspects of the posts.
I dropped empty and redundant columns to simplify the analysis. For example, the Reactions and Organic Impressions columns were duplicates of the Likes and Impressions columns, respectively. The App Install Attempts column had only zeros.

## Data Exploration
To explore the data after preparation, I used various techniques such as descriptive statistics, bar charts and line plots. I also used knowledge on social media to interpret the results and provide insights. While exploring, I found that Photo is the most frequently posted content type, most posts contain Hashtag, fewer posts contain question, most posts are of medium lengths, majority of the posts sounded neutral to the audience. I also came up with some hypotheses and tested them using the ANOVA and Linear regression statistical tests. The hypotheses tested includes:
1: Positive tones generate the highest Engagement Rate per Impression than any other posts. 
2: There are no significant differences in the Engagement Rate per Impression of Content Tones. 
3: The tone of a caption/post is the most important feature for generating interactions for a post 
4: There are no significant differences in the Average interactions of Content Types

## Results, Conclusion and Recommendation
The engagement rate (per impression) varies according to the tone of the post: Negative tone has 2.57, Neutral Tone has 2.59, and Positive Tone has 2.67. An ANOVA test with a p-value of 0.02 shows that this difference is not due to chance. Therefore, we can conclude that Positive Tone leads to more engagement per impression than other tones.

Using linear regression to measure the feature importance of different aspects of a post. it can be concluded that the most important features for each outcome are:

Engagement rate (per impression): Linking to other contents or posts, asking questions, and using hashtags.
Likes: Using positive tone and asking questions.
Comments: Linking to other contents and asking questions.
Virality: Asking questions and using action words.
Click-Through rate: Linking to other contents, using action words, and using a neutral tone.

### Recommendation
Based on the above results and conclusions, the following are recommended.

- To increase the engagement rate of twitter posts, use a Positive Tone in captions. This will make the posts more appealing and attractive to the audience, and encourage them to interact with the content.
- Link posts to relevant or interesting contents or posts, ask questions that invite the audience to share their opinions or experiences, and use hashtags that are popular or related to your topic to boost engagement rate per impression.
- Use positive tone and ask questions that show your interest in your audience or your topic to generate more likes.
- Link posts to other contents or posts that spark a discussion or a debate, and ask questions that challenge the audience or provoke their curiosity in order to generate more comments
- To make post go viral, ask questions that are catchy, controversial, or surprising, and use action words that urge the audience to act or share the post.
- For click-through rate to improve, Link posts to other contents that are informative, useful, or entertaining, use action words that create a sense of urgency, curiosity, or excitement, and use a neutral tone that is clear, concise, and professional.
