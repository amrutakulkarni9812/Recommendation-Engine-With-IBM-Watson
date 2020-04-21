![Alt text](https://uploads.toptal.io/blog/image/125351/toptal-blog-image-1517915383695-cfef65b3d04c9f280f5d7f7a50465aeb.png?raw=true "Recommendation Systems")
# Recommendation-Engine-With-IBM-Watson
IBM has an online data science community where members can post tutorials, notebooks, articles, and datasets.
In this project,I have built a recommendation engine based on user article interactions.
## Instructions:
1. Run the ipython notebook to get recommendation results and visualizations.
## Installation
Beyond the Anaconda distribution of Python, the following packages need to be installed:
  nltk.punkt
  nltk.wordnet
  nltk.stopwords
## Datasets Introduction
There are two files: 
1. data/user-item-interactions.csv: the articles each user has viewed
2. data/articles_community.csv: details of the articles
## Project Motivation
The goal of this project is applying concepts of rank based recommendations, content based recommendations, and user-user collaborative filtering.
This will help IBM Watson Studio users to get relevant recommendations on next reads and keep them engaged.
## Analysis:
1.Collaborative Filtering
Takes into account the similarity of users and recommends the most popular articles read by similar users
Rank Based Recommendations
Recommends the top ranked articles starting with the most highly ranked
Content Based Filtering
Produces recommendations based on similarity to material the user has interacted with previously. Utilizes Natural Language Processing (NLP) methodology to analyse and rank articles by similarity.
SVD - Matrix Factorization Recommendations
Utilises matrix operations to predict the ranking (or in this case the boolean interaction variable)
## Acknowledgement
Thanks to Udacity Data Scientist Nanodegree content creators for providing us the opportunity to work on this project.
