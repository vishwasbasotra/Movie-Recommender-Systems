# Movie Recommender Systems
Recommender systems are algorithms designed to help users discover movies, products, and songs by predicting the user’s rating of each item and displaying similar items that they might rate high as well. The objective is to show customers content that they would like best based on their historical activity. 

## We will discuss two types of recommender systems:

__Demographic Filtering__- They offer generalized recommendations to every user, based on movie popularity and/or genre. The System recommends the same movies to users with similar demographic features. Since each user is different , this approach is considered to be too simple. The basic idea behind this system is that movies that are more popular and critically acclaimed will have a higher probability of being liked by the average audience.

__Collaborative Filtering__- This system matches persons with similar interests and provides recommendations based on this matching. Collaborative filters do not require item metadata like its content-based counterparts.

### Collaborative Filtering:
__Recommender Systems: User-Based Collaborative Filtering__
- User-based collaborative filtering works by building a matrix of every piece of content that users bought or viewed. 
- Similarity scores are then calculated between users to find similar users to each others. 
- For similar users, content that have not been viewed or bought are recommended to users that haven’t seen them before.

__Recommender Systems: User-Based Collaborative Filtering Limitations__
- More users than products, movies..etc so making the problem more complex (~8 billion people!)
- Users taste change over time. 
- Let’s explore another strategy that overcomes the limitations of User-based collaborative filtering. This strategy is named item-based collaborative filtering.

__Recommender Systems: Item-Based Collaborative Filtering__
- Item-based collaborative filters work by recommending elements based on relationship between items and not people. 
- The recommender system is now designed based on items (such as movies) and not users. 
- This reduces the complexity of the problem and overcomes the challenges of user-based collaborative filtering. 
- Unlike humans, movies, songs, and products features and tastes do not change over time. 
