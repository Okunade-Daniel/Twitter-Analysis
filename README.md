# The Effect of Tone and Content-Type on Brand Social Media Interactions
# Overview
Social media is a powerful tool for brands to communicate with their customers, promote their products, and build their reputation. However, not all social media posts are equally effective in generating engagement from the audience. The tone and content type of a post can influence how the audience reacts to it, and thus affect the brand’s social media performance.

# Objective
This analysis aims to investigate the relationship between the tone and content type of social media posts and the level of engagement they generate. The analysis will focus on three types of tones: positive, neutral, and negative, and the various types of content available in the dataset.

Data
The data used for this analysis is a sample of 8,529 Twitter (now X) posts. The data contains 147 variable including:


Post: The text of the post
Content Type: The type of content, such as image, video, link, text, etc.
Tone: The tone of the post, classified as positive, neutral, or negative
Likes: The number of likes that the post received
Comments: The number of comments that the post received
Shares: The number of shares that the post received
Impression: The number of times a post was seen
Engagement: The number of times a post was interacted with
Engagement Rate per Impression: The ratio of the total number of impression to the number of Engagements of the brand etc.
# Methodology
The analysis will use descriptive statistics and inferential statistics to explore the data and test the following hypotheses:

H1: Positive tones generate the highest Engagement Rate per Impression than any other posts.
H2: There are no significant differences in the Engagement Rate per Impression of Content Tones.
H3: The tone of a caption/post is the most important feature for generating interactions for a post
H4: There are no significant differences in the Average interactions of Content Types

The analysis will use the following tools and techniques:

Python: A programming language for data analysis and visualization
Pandas: A library for data manipulation and analysis
Numpy: A library for scientific computing and linear algebra
Matplotlib: A library for plotting and graphing
Seaborn: A library for statistical data visualization
Scipy: A library for scientific and technical computing
Sklearn: A library for machine learning and data mining

#### Results and Conclusion
- The engagement rate (per impression) varies according to the tone of the post: Negative tone has 2.57, Neutral Tone has 2.59, and Positive Tone has 2.67. A statistical test with a p-value of 0.02 shows that this difference is not due to chance. Therefore, we can conclude that Positive Tone leads to more engagement per impression than other tones.

- Using linear regression to measure the feature importance of different aspects of a post. it can be concluded that the most important features for each outcome are:

 - - Engagement rate (per impression): Linking to other contents or posts, asking questions, and using hashtags.
 - - Likes: Using positive tone and asking questions.
 - - Comments: Linking to other contents and asking questions.
 - - Virality: Asking questions and using action words.
 - - Click-Through rate: Linking to other contents, using action words, and using a neutral tone.



#### Recommendation

Based on the above conclusions, the following are recommended.
- To increase the engagement rate of twitter posts, use a Positive Tone in captions. This will make the posts more appealing and attractive to the audience, and encourage them to interact with the content.
- Link posts to relevant or interesting contents or posts, ask questions that invite the audience to share their opinions or experiences, and use hashtags that are popular or related to your topic to boost engagement rate per impression. 
- Use positive tone and ask questions that show your interest in your audience or your topic to generate more likes. 
For comments: Link your posts to other contents or posts that spark a discussion or a debate, and ask questions that challenge your audience or provoke their curiosity.
For virality: Ask questions that are catchy, controversial, or surprising, and use action words that urge your audience to act, share, or join.
For click-through rate: Link your posts to other contents that are informative, useful, or entertaining, use action words that create a sense of urgency, curiosity, or excitement, and use a neutral tone that is clear, concise, and professional.
