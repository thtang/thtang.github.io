---
title: "ACM WSDM Cup 2019 - Fake News Classification"
excerpt: "WSDM is one of the premier conferences on web-inspired research involving search and data mining. One of the task in WSDM Cup 2019 is to detect the fake news. Given the title of a fake news article A and the title of a coming news article B, participants are asked to classify B into one of the three categories. My method is ranked **6/8 (public/private)** among **94** teams from all over the world. [See Kaggle competition](https://www.kaggle.com/c/fake-news-pair-classification-challenge).<br/><img src='/images/WSDMCUP.png' width='500'>"
collection: portfolio
---
# Background:

This task is organized by ByteDance, the Platinum Level Sponsor of the conference. ByteDance is a global Internet technology company started from China. Our goal is to build a global content platform that enable people to enjoy various content in various forms. We inform, entertain, and inspire people across language, culture and geography.
One of the challenges which we are facing is to combat different types of fake news. Fake news here refers to all forms of false, inaccurate or misleading information, which now poses a big threat to human civilization.
At Bytedance, we have created a large-scale database to store existing fake news articles. Any new article must go through a test on the truthfulness of content before being published. We conduct matching between the new article and the articles in the database. Articles identified as containing fake news will be withdrawn after human verification. The accuracy and efficiency of the process, therefore, becomes crucial for us to make the platform safe, reliable, and healthy.

# About the Task:

Task: classification of news article
Given the title of a fake news article A and the title of a coming news article B, participants are asked to classify B into one of the three categories.
* agreed: B talks about the same fake news as A
* disagreed: B refutes the fake news in A
* unrelated: B is unrelated to A

<img src='/images/WSDM_result.png' width='600'>