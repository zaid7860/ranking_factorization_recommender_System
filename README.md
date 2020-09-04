# recommandation-system-turicreate
# Recommandation system on goodbooks dataset kaggle using  turicreate library

There have been good datasets for movies (Netflix, Movielens) and music (Million Songs) recommendation, but not for books. That is, until now.

This dataset contains ratings for ten thousand popular books. As to the source, let's say that these ratings were found on the internet. Generally, there are 100 reviews for each book, although some have less - fewer - ratings. Ratings go from one to five.

Both book IDs and user IDs are contiguous. For books, they are 1-10000, for users, 1-53424. All users have made at least two ratings. Median number of ratings per user is 8.

There are also books marked to read by the users, book metadata (author, year, etc.) and tags.


# Dependencies 

pip install turicreate
pip install pandas

NOTE: as of 8th September 2020 , Turicreate is not available for Windows.

# ranking_factorization_recommender
