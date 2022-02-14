# Recommendation_Engine
Recommending electronic product in a e-commerce platform using popularity based model for cold start and collaborative filtering for existing customer with preference history

## Project Overview

These days, recommendation engine is very powerful to tackle information overload. Imagine you go to your favorite e-commerce platform and there are tons of random product shown in your homepage. It's pretty annoying innit?
This is where the recommendation engine will come in handy where it will show the relevant items for you only, based on your past behaviour/preferences or based on user that has similiar taste like you. 

This project is a recommendation engine for electronic product in an e-commerce platform that is suitable for 2 conditions :
1. Popularity based model  
   We use this approach when there is new user coming on to the platform where we don't have any past information about this customer. 
   The popularity based model recommends products that popular among the existing users (many other users have rated these products) to the new user
  
2. Collaborative filtering  
   We use this approach when we have information about past customer preferences. 
   Collaborative filtering is a widely used algorithm for recommendation engine when the user is recommended items based on similiar user preferences. This method predicts unknown ratings by using the similarities between users.

## Requirement

In this project, we use python and surprise library for the collaborative filtering algorithm. 

## Data

The data is from amazon electronic product recommendation [HERE](https://www.kaggle.com/prokaggler/amazon-electronic-product-recommendation)

## References

https://www.kaggle.com/prokaggler/amazon-product-recommendation  
https://towardsdatascience.com/building-and-testing-recommender-systems-with-surprise-step-by-step-d4ba702ef80b

## Contact

For more inquiries you can reach me at deasymp.093@gmail.com

