# Reddit Language Modeling
We train n-gram trees, GPT2, and BERT, on Kaggle Reddit data. 

- We build generative models with N-gram trees and GPT2 (distilGPT2) to generate text from specific categories of subreddits

- We use BERT (distilBert) to build a classifier to label text into one of 5 subreddit categories

- We use BERT again to train a classifier that can tell generated text from real text.