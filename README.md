# RECOMMENDATION-SYSTEM

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: JUDITH LEO CHRISTOPHER

*INTERN ID*: CT04DL1408

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4WEEKS

*MENTOR*: NEELA SANTOSH

**DESCRIPTION: This code provides a recommender system based on collaborative filtering, specifically using matrix factorization with bias terms. It runs through loading a user-item-rating dataset MovieLens 100k, converting user and item IDs to their internal index, and dividing the dataset into training and test datasets. The matrix_factorization function uses stochastic gradient descent to minimize the squared error between prediction of ratings based on the latent user and item matrices, and actual ratings - if the user and item are present in the training set, their bias values are also taken into account. It then uses the trained model to assess performance on the test set, calculating the root mean squared error. Finally, it provides a function to predict the top N recommendations for a given user, this would involve calculating a predicted rating for every item and selecting those with the highest predicted score.

*output*:

![Image](https://github.com/user-attachments/assets/0de74968-2f3f-4bba-94c4-0073c8cd61a6)
