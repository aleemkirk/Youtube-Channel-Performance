# Introduction
Since its inception in 2005, YouTube has drastically altered the digital media landscape. More than just a video-sharing platform, it enables people from all corners of the world to create and share content independently of traditional media recognition. As of 2023, YouTube has amassed an impressive 2.70 billion users, making it the second-largest social media site globally. This diverse platform, offering everything from educational materials to entertainment, plays a significant role in shaping trends and public opinion. Its financial impact is notable, generating $14.358 billion in the first two quarters of 2023, highlighting its importance to content creators and advertisers. YouTube has become a central influencer across various fields, revolutionizing information sharing.

Beyond entertainment, YouTube serves as a hub for community building, learning, and personal expression. It has democratized content creation, allowing individuals worldwide to share their stories and talents, challenging the status quo in the entertainment industry. Despite facing challenges in content moderation, YouTube remains committed to ensuring a balance between freedom of expression and a safe, respectful environment. As the platform continues to grow and innovate, it is set to maintain its position as a foundational element of digital media and a significant influencer online.

This report delves into YouTube's content strategy and user engagement. Utilizing various statistical methods to analyze data, the study aims to reveal how video characteristics, upload frequencies, and types of content impact viewer behavior and engagement. This understanding is vital for content creators and marketers, offering essential insights for optimizing content strategy on this dynamic platform. The study's importance extends beyond academic interest, providing practical applications to enhance digital media strategies in the ever-evolving world of YouTube.

# Hypothesis 
The primary problem addressed in this project revolves around optimizing content strategy and enhancing user engagement on YouTube, a platform with over 2.70 billion users. Despite its vast user base, content creators often face challenges in effectively engaging their audience and growing their channels. To address this, the project aims to test several hypotheses using data available through the YouTube API:
* H1: Video Length and View Count: Whether there is a correlation between the length of videos and the number of views they receive.
* H2: Upload Frequency and Engagement: Investigating if channels that upload more frequently experience higher overall engagement.
* H3: Content-Type and Subscriber Growth: Assessing if certain types of content are more effective in driving subscriber growth.
* H4: Channel Age and View Count: Analyzing if channel age influences video performance.

# Models

## Model 1
$$\left(View\ Count\right)=\beta_0+\beta_1\left(Video\ Length\right)+\beta_2\left(Subscriber\ Count\right)+\beta_3\left(Channel\ Age\right)+\beta_{4_i}\left(Video\
Category\right) +\beta_{5_i}\left(Video\ Length\right)\ast\left(Video\ Category\right)+\beta_{6_i}\left(Subscriber\ Count\right)\ast\left(Video\ Category\right)+\ \beta_{7_i}\left(Channel\ 
Age\right)\ast\left(Video\ Category\right)$$

## Model 2
$$log\left(View\ Count\right)=\beta_0+\beta_1log\left(Video\ Length\right)+\beta_2log\left(Subscriber\ Count\right)+\beta_3log\left(Channel\ Age\right)+\beta_{4_i}\left(Video\ Category\right)+\beta_{5_i}log\left(Video\ Length\right)\ast\left(Video\ Category\right)+\beta_{6_i}log\left(Subscriber\ Count\right)\ast\left(Video\ Category\right)+\
\beta_{7_i}log\left(Channel\ Age\right)\ast\left(Video\ Category\right)$$

# Results
![image](https://github.com/aleemkirk/Youtube-Channel-Performance/assets/24708127/ba02bc88-6c37-4fe8-81af-7caf1c866ee4)




