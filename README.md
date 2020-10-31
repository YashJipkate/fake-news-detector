# Fake News Detection Using Deep Learning
Project for CSE362 Data Mining

## Motivation
Fake news is widely spread across social networks. Therefore, there is a huge demand to debunk fake news. These fake news are responsible for spreading negativity,
harassment of particular races and groups and demeaning people belonging to certain
ethnicities. There are many attempts to detect fake news but limited work is about using
Deep Learning models. In this project, we aim to build state-of-the-art deep learning
models to detect fake news based on the content of the article itself.

# Dataset
We get the ground truth data from [kaggle](https://www.kaggle.com/arminehn/rumor-citation/data#). We only use Snopes URLs since the labels of each news were clearly presented. Only "true" or "false" labels were kept. We randomly select 281 true news and 281 false news and crawl the Snope website for additional content.

