# Recommendation System
A recommendation system or also known as recommender system is a subclass of information
filtering system that seeks to predict the "rating" or "preference" a user
would give to an item. They're primarily used in commercial applications.

There are some possible data utilty in a recommendation system:
- history
- like
- dislike
- rating, etc.

In these codes, tried to build a better anime recommendation system based only on
user viewing history and will use user-based collaborative filtering to do the task.

In user-based collaborative filtering:
- users are deemed similar if they like similar items
- first discover which users are similar
- then recommend items that other similar users like

To build a model, used python library such as:
- matplotlib
- pandas
- seaborn
- statistics
- sklearn
- operator

Model will find the most similar users by using theory of "cosine similarity" that
measures the similarity between vectors of an inner product space.
It's measured by the cosine of the angle between two vectors and determines
whether two vectors are pointing in roughly the same direction.

Cosine similarity is often used to measure document similarity in text analysis.
