# Music recommender system

A **recommender system** is a type of information filtering system that suggests items to users based on their preferences and behavior. It uses data analysis techniques to understand a user's behavior and to predict what they might like or be interested in.

There are two main types of recommender systems:

**Content-based recommender systems**: This type of system analyzes the characteristics of the items a user has interacted with, such as the content of a movie or the genre of a book, to recommend similar items. However, these algorithms try to recommend items similar to those that a user liked in the past. It does not rely on a user sign-in mechanism to generate this often temporary profile. As a result, the surprisal element is missing in the recommendation as same kind of content gets recommended.

**Collaborative filtering recommender systems**: This type of system analyzes the behavior of multiple users to recommend items that are popular among users with similar interests. Among collaborative-based systems, we can encounter two types: user-item filtering and item-item filtering.

Recommender systems are used in a variety of applications, such as e-commerce websites, social media platforms, and music and video streaming services, to personalize the user experience and improve engagement. They can also help businesses increase revenue by suggesting additional products or services that a user might be interested in.

**The aim of this project is to:**

1) Generate a content-based music recommender system using a dataset of name, artist, and lyrics for 57650 songs in English obtained from Kaggle. The data has been acquired from LyricsFreak through scraping by the author.

2) Build a collaborative filtering music recommeder system using the Million Song Dataset; a freely-available collection of audio features and metadata for a million contemporary popular music tracks.

This repo is divided into the following two packages that contains the following files:
    
I. Content based music recommender system:

a.  A jupyter notebook named `content based music recommender system` that contains the code and analysis for the recommedation system.
b.  A `CSV` file named `songdata` containing the data for the songs used in the system.

II. Collaborative filtering recommender system:

a. A jupyter notebook named `collaborative filtering music recommender system` that contains the code and analysis for the recommedation system.
b. Four `CSV` files named `songs`, `song_extra_info`, `members` and `train` containing the data for the songs used in the system.
