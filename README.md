# Introduction
Since its inception in 2005, YouTube has drastically altered the digital media landscape. More than just a video-sharing platform, it enables people from all corners of the world to create and share content independently of traditional media recognition. As of 2023, YouTube has amassed an impressive 2.70 billion users, making it the second-largest social media site globally. This diverse platform, offering everything from educational materials to entertainment, plays a significant role in shaping trends and public opinion. Its financial impact is notable, generating $14.358 billion in the first two quarters of 2023, highlighting its importance to content creators and advertisers. YouTube has become a central influencer across various fields, revolutionizing information sharing.

Beyond entertainment, YouTube serves as a hub for community building, learning, and personal expression. It has democratized content creation, allowing individuals worldwide to share their stories and talents, challenging the status quo in the entertainment industry. Despite facing challenges in content moderation, YouTube remains committed to ensuring a balance between freedom of expression and a safe, respectful environment. As the platform continues to grow and innovate, it is set to maintain its position as a foundational element of digital media and a significant influencer online.

This report delves into YouTube's content strategy and user engagement. Utilizing various statistical methods to analyze data, the study aims to reveal how video characteristics, upload frequencies, and types of content impact viewer behavior and engagement. This understanding is vital for content creators and marketers, offering essential insights for optimizing content strategy on this dynamic platform. The study's importance extends beyond academic interest, providing practical applications to enhance digital media strategies in the ever-evolving world of YouTube.

# Hypothesis 
The primary problem addressed in this project revolves around optimizing content strategy and enhancing user engagement on YouTube, a platform with over 2.70 billion users. Despite its vast user base, content creators often face challenges in effectively engaging their audience and growing their channels. To address this, the project aims to test several hypotheses using data available through the YouTube API:
* H1: No correlation between video Length and view Count.
* H2: No correlation between subscriber count and view count.
* H3: No correlation between channel Age and view Count.

# Models

## Model 1
$$\left(View\ Count\right)=\beta_0+\beta_1\left(Video\ Length\right)+\beta_2\left(Subscriber\ Count\right)+\beta_3\left(Channel\ Age\right)+\beta_{4_i}\left(Video\
Category\right) +\beta_{5_i}\left(Video\ Length\right)\ast\left(Video\ Category\right)+\beta_{6_i}\left(Subscriber\ Count\right)\ast\left(Video\ Category\right)+\ \beta_{7_i}\left(Channel\ 
Age\right)\ast\left(Video\ Category\right)$$

## Model 2
$$log\left(View\ Count\right)=\beta_0+\beta_1log\left(Video\ Length\right)+\beta_2log\left(Subscriber\ Count\right)+\beta_3log\left(Channel\ Age\right)+\beta_{4_i}\left(Video\ Category\right)+\beta_{5_i}log\left(Video\ Length\right)\ast\left(Video\ Category\right)+\beta_{6_i}log\left(Subscriber\ Count\right)\ast\left(Video\ Category\right)+\
\beta_{7_i}log\left(Channel\ Age\right)\ast\left(Video\ Category\right)$$

# Results
## Model 1 OLS Performance
![image](https://github.com/aleemkirk/Youtube-Channel-Performance/assets/24708127/aa0b337d-0518-49a5-a170-0686ddfa53f0)
![image](https://github.com/aleemkirk/Youtube-Channel-Performance/assets/24708127/03191fd9-0936-4cb3-93f3-447be9aaf39b)



## Model 2 GLM Performance
![image](https://github.com/aleemkirk/Youtube-Channel-Performance/assets/24708127/7c5c9b8c-9406-4ed8-b2b7-7ed473d8e747)
![image](https://github.com/aleemkirk/Youtube-Channel-Performance/assets/24708127/e9a2d123-1e18-4aea-8f9a-a38d294bf9ff)

# Regression Tables
Green indicates top 10% of values and red indicates the bottom 10% of values. 
![image](https://github.com/aleemkirk/Youtube-Channel-Performance/assets/24708127/c4e0a6bf-99e4-4f77-ab24-a8c39372ac82)

# Conclusion 
The problem statement revolves around optimizing content strategy and enhancing user engagement. The study tests hypotheses on relationships between video length, content type, subscriber count, and channel age using data from the YouTube API.
The methodology involves a systematic approach, focusing on channels with ≥100,000 subscribers and videos posted after January 1, 2023. Data extraction via a Python script, storage in a MySQL database, and statistical analyses in R are employed. Model selection incorporates a log-transformed model, and a generalized linear model, comparing their performance. Results indicate the generalized linear model works best when predicting out of sample data. According to the generalized linear model, animal, fashion, and how-to videos are most positively affected by video length and education, exercise and gaming videos are most negatively affected. Religion, exercise, and technology videos are most positively affected by subscriber count while documentaries, music, and sports videos are the most negatively affected. Documentaries, gaming, and vehicle videos are most positively affected by channel age whereas fashion, politics and technology videos are most negatively affected. 












