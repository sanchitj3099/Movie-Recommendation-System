# Movie-Recommendation-System
Creating a content based filter to create a list for the user to find movies similar to that he is interested in while also performing certain visual analysis on the data at hand.


## About The Dataset
The dataset that is being used here has been extracted from the generic Kaggle repository, which has about 16000+ movies with the relevant information regarding its rating, content, genre, etc. This dataset allows for a much more comprehensive analysis due to its size and extensive information about the movies.

## Content Based Filtering
Content based filtering is a methodology that allows for the system to recommend movies or any other entity based on similar items present in the dataset.This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person likes a particular item, he or she will also like an item that is similar to it. And to recommend that, it will make use of the user's past item metadata.

## IMPORTANT MODULES
### CountVectorizer
This helps in creating tokens of the categorical data and arrange them into a matrix. And helps remove stopwords from the text.
### Cosine_similarity
Cosine similarity, or the cosine kernel, computes similarity as the normalized dot product of X and Y: K(X, Y) = <X, Y> / (||X||*||Y||) On L2-normalized data, this function is equivalent to linear_kernel. Parameters X{ndarray, sparse matrix} of shape (n_samples_X, n_features) Input data.
