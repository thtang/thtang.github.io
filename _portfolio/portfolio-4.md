---
title: "NTU-HTC Deep Learning Competition: Weakly Supervised Learning for Findings Detection in Medical Images"
excerpt: "In this task, we have to plot bounding boxes for each disease finding in a single chest X-ray without goundtruth (X, Y, width, height) in training set. The task description is detailed in [PDF 1](https://www.csie.ntu.edu.tw/~yvchen/f106-adl/doc/HTCIntro.pdf) and [PDF 2](https://www.csie.ntu.edu.tw/~yvchen/f106-adl/doc/HTCMedical.pdf). Our work flow could be summarized as <br/><img src='/images/process_flow.png' width='500'>"
collection: portfolio
---
# Background:

An increasingly wide range of personal devices, such as smartphones, video cameras as well as wearable devices that allow capturing pictures, videos, and audio clips in every moment of our life are becoming available. Considering the huge volume of data created, commonly referred to as lifelogs, there is a need for systems that can automatically analyse the data in order to categorize, summarize and also query to retrieve the information the user may need.

# About the Task:

## Dataset:
* The task will be split into two related subtasks using a completely new multimodal dataset which consists of 90 days of data from two lifeloggers, namely: images (1,500-2,500 per day from wearable cameras), visual concepts (automatically extracted visual concepts with varying rates of accuracy), semantic content (semantic locations, semantic activities) based on sensor readings (via the Moves App) on mobile devices, biometrics information (heart rate, galvanic skin response, calorie burn, steps, etc.), music listening history, computer usage (frequency of typed words via the keyboard and information consumed on the computer via ASR of on-screen activity on a per-minute basis). The dataset is based on the data available for the NTCIR-13 - Lifelog 2 task. A lifelog baseline search engine API will be provided by the task organizers.

## SubTask 1: Activities of Daily Living understanding (ADLT)
Given a period of time, e.g., "From 13 August to 16 August" or "Every Saturday", the participants should analyse the lifelog data and provide a summarisation based on the selected concepts (provided by the task organizers) of Activities of Daily Living (ADL) and the environmental settings / contexts in which these activities take place.

Some examples of ADL concepts: "Commuting (to work or another common venue)", "Travelling (to a destination other than work, home or another common social event)", "Preparing meals (include making tea or coffee)", "Eating/drinking", and contexts: "In an office environment", "In a home", "In an open space". The summarisation should be described as the frequency and spending time for ADL concepts and total time for contexts concepts. For example:

* ADL: “Eating/drinking: 6 times, 90 minutes”, “Travelling: 1 time, 60 minutes”;
* Context: “In an office environment: 500 minutes”, “In a church: 30 minutes”.

## SubTask 2: Lifelog moment retrieval (LMRT)
The participants have to retrieve a number of specific moments in a lifelogger's life. We define moments as semantic events, or activities that happened throughout the day. For example, they should return the relevant moments for the query “Find the moment(s) when I was shopping for wine in the supermarket.” Particular attention should be paid to the diversification of the selected moments with respect to the target scenario.

The ground truth for this subtask was created using manual annotation.