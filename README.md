# PvZMLChallenge Round#1 2019 Dec Announcement

## Announcers
Jack_Gu@PPSUC, Molasses@ZJNU

## Story

![tiny_logo.png](https://i.loli.net/2019/12/10/kqNP8gjUpirvCDZ.png)

Welcome! This is **P**PSUC **v**s. **Z**JNU **M**achine **L**earning **C**hallenge (abbr. **PvZMLC**), a mini team contest founding for better understanding of machine learning algorithms including the classical and the deep.

The topic missions in the PvZMLC are well designed around the fields of data mining and computer vision in order to take advantages of two research group directions. The goals of the contest are to examinate how good participators have learnt about machine learning algorithms and to reflect how to apply those amazing papers to complicated but funny scenes. We believe that this progress will show algorithms are not cold and dull mathematics all the time but reachable and available. Just relax and enjoy! The winning or losing is not important and we hope to hold an interesting studying event for everyone, two groups of friends. 

As the founders of PvZMLC, we both are so excited to announce the very first round topic. Action stations!

## Round#1 Air Quality Forecast

### Notice

**Round Type** structured data mining / analysis, visualization

**Dataset** Dataset for Air Quality Forecast

- Neither other data nor datasets are **allowed** to use during any step of your work.

**Alogrithms** classicals

- Neural network is **not allowed**.

**Time** 2019/12/14-2019/12/20

**Players** 4 players, 1 coach

**Solution** choose one to submit: kernels(colab, jupyter), codes with documents

- Your code style should be regular; your comments should be readable. 

- A short report is needed to share your team's ideas.

**Judge** code review, presentation

- An online review meeting is going to be held as the end of Round#1; on the meeting, everyone will listen to team reports and topic setters' opinions.

### Introduction

As we all know, there are many ways to divide data types. For example, it can be divided into structured data, semi-structured data, and unstructured data. But in the process of processing, we will find that although such a division is obvious, it can not play much role in the later analysis. This is one of the problems we often make in data analysis, that is, the work of data governance does not rely on modeling and analysis.

![flow1.png](https://i.loli.net/2019/12/11/rIXnS4eCOmTlvty.png)

Therefore, according to the data collection scene and its attributes, we can divide the data into entity data, sensor data, and event data. Entity data, that is, its own data such as attributes, status, and capabilities. sensor data, that is, data generated by entities, can generally be divided into several types such as numerical values, pictures, text, and videos. Event data, that is, structured information data.

![flow2.png](https://i.loli.net/2019/12/11/nDIBEwKVUQRYgCj.png)

The entity is data that everyone is very familiar with, such as demographic data that can be used for user portraits, and also a data set that everyone is very familiar with iris. Sensor data is more complex and diverse than entity data. Generally speaking, it can be divided into six categories: spatio-temporal static point / network data, spatio static temporal dynamic point / network data, and spatio-temporal dynamic point / network data. In addition to the characteristics of the event itself, the event data also contains rich contextual information. An event is data generated in a spatio-temporal range, and it establishes a special relationship for the data in this spatio-temporal range.

Generally speaking, based on the difficulty of data analysis, entity data is the easiest to analyze. Because entity data contains very little dynamic information, the information that can be mined from it is limited. Compared with the entity data, the sensor data has more contextual information. This information can help us to establish the time series model of the entity itself and the time series model of interaction between multiple entities. It contains the largest amount of information, and the most difficult to analyze is event data, which includes both dynamic / static associations between entities and time series, and more importantly, the causal relationships inherent in it.

The recent rise of deep learning has led everyone to focus on building models. Thus, unfortunately, beginners often overlook the properties of the data itself and its applicable scenarios. We try to reduce participators' misunderstanding and bias on data analysis. Meanwhile, we hope everyone can find the meaning of data mining during this round. We carefully selected the appropriate data set to locate the first round in the spatio static temporal dynamic point data in the relatively simple but still challenging sensory class of sensor data.

## Mission

### PART.I Feature Engineering

Although there are many representational models that claim to be able to replace the work of manual feature extraction, we still cannot ignore the role of many manual features, because the features learned by representational learning are not necessarily the actual relationship, but only the coincidence correlation. Now more and more studies show that the prior bias in the input features will greatly affect the final result, and these prior biases are often unlearned by the model, because the ability of most models lies in fitting, not in judging whether the relationship is correct. 

We wanted participants to **1) extract as many features as possible from the data, 2) while assessing whether these features were important for classification questions and regression questions, respectively (each answer: yes/no)**.

### PART.II Prediction

The target in second part is to **predict the next 7-day air quality through at least 2 ways to predict.**

We recommend that you provide performance reports on your models, otherwise it may not be fair to judge them solely on the final results.

### PART.III Classification & Clustering

At this part, you need to use **classification** or **clustering** methods to mining implicit patterns. It's an open proposition, so just start your brainstorm. We offer some reference suggestions: **mining from multiple dimension combination level of data, mining from evolution level of single dimension value.**

## Helps

Some utilities and references are provided in [Round#1 Wiki](https://github.com/PvZMachineLearningChallenge/Round1/wiki).
