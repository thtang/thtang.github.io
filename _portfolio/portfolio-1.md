---
title: "IEEE ICME 2019 Grand Challenge - Short Video Recommendation"
excerpt: "ICME is one of the flagship conferences in multimedia. In this competition, participants are asked to predict whether a user will finish and like a specific short video along with its multi-modal features. My solution is ranked $3^{rd}$ out of **1028** teams from all over the world. [See competition LeaderBoard](https://biendata.com/competition/icmechallenge2019/)<br/><img src='/images/6634005837125779463.png'>"
collection: portfolio
---
ICME2019 & Bytedance Inc. • $20,000 • 1028 teams • 2433 participants

# Background

In recent years, deep learning has made great progress in several fundamental tasks such as image recognition and speech recognition, but there are still many problems to be explored in the field of video content understanding.
The TikTok (Douyin overseas edition) APP, a product of Bytedance and a short video social platform powered by music, has received wide acclaim from users around the world. Therefore, the understanding and recommendation technology of short video has been the focus of our Bytedance's attention.
A picture is worth thousands of words. One picture contains a large amount of information which is difficult to be described in a few words, not to mention more rich media such as short videos. Currently, Bytedance has tons of short video clips and the behavior data of hundreds of millions of users who watched them. Therefore, Bytedance has enough video content and user behavior data to predict users' preference for short videos.
This challenge provides multi-modal video features, including visual features, text features, and audio features, as well as user interactive behavior data, such as click, like, and follow. Each participant needs to model the user's interest through video features and user interaction behavior data set, and then predict the user's click behavior on another video dataset. 
The leaderboard will use the method which is described on the evaluation webpage to score the results submitted by the participants.

# Task
 
The challenge asks participants to predict the probability that each user finishes watching and likes a given video of test dataset.
We use AUC (area under ROC curve) as our challenge metric. The higher the AUC, the higher the ranking.

For our published paper, please refer to [Publication](https://thtang.github.io/publication/2009-10-01-paper-title-number-1)