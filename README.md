
# Book-Recommendation-using-collaborative-approach

![d](https://user-images.githubusercontent.com/102940106/183637598-f6db26dd-37ad-4d4b-af49-b87c72bac0f1.jpg)


# **Introduction**
**What is a Recomendation System?**
Recommender systems or Recommendation systems aim to predict users’ interests and recommend product items that quite likely are interesting for them. They are among the most powerful machine learning systems that online retailers implement in order to drive sales.

There are two primary types of recommender systems:

Collaborative Filtering Systems: These types of recommender systems are based on the user’s direct behavior. That is, this system builds a model of the user based on past choices, activities, and preferences. It then uses this knowledge to predict what the user will like based on their similarity to other user profiles.

Content-Based Filtering System: Content-based recommender systems, on the other hand, are based on the items, and not necessarily the users. This method builds an understanding of similarity between items. That is, it recommends items that are similar to each other in terms of properties.


# **Problem Statement**

In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries).

Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create a book recommendation system for users.

# **Dataset**
This Book-crossing dataset contains three files: Users, Books, Ratings.
2324

* Contains three datasets: books, users and ratings.

There have been good datasets for movies (Netflix, Movielens) and music (Million Songs) recommendation, but not for books. That is, until now.

This dataset contains ratings for ten thousand popular books. As to the source, let’s say that these ratings were found on the internet. Generally, there are 100 reviews for each book, although some have less - fewer - ratings. Ratings go from one to five.

**Exploratory data analysis (EDA):**

Visualization on some important parts like most rated books, most popular books, most popular authors, most number of ratings
Data Preprocessing:

* Data cleansing
* Nan value treatment
* Extraction of relevant featuress
* Model building:


There are also books marked to read by the users, book metadata (author, year, etc.) and tags.
* Performed Data Preprocessing on these three datasets and then merged them.
* Performed EDA to get insights on users, books etc.
* Used Popularity based and Collaborative filtering based approaches for our recommender system.
* For Collaborative filtering: Memory (Item-Item) and Model (User-User) based approaches.
* Implemented KNN based algorithm for Memory based system and SVD for Model based system.

