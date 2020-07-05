# User-Based-Collaborative-Filtering

There is one famous quote about customer relationship. The summary of the quote like this <b>"Customers don't know what they want until we show them."</b> So Recommendation Systems will help customers to find information, product & services they might not have thought of.


Music, T.V., Retail are one of the examples in Recommendation Systems.

There are many types of Recommendation Systems exists but for this project i created - <b>USER BASED COLLABORATIVE FILTERING.</b>

In this algorithm finds the similarity score between users. Based on this similarity score, it then picks out the most similar users and recommends products. For similarity we can make use of PEARSON CORRELATION or K-NN using euclidean distance

#### Steps for User Based Collaborative Filtering
- Create a sample dictionary of users with web series and their ratings
- Create a function to print the unique set of web series
- Create a function to implement pearson correlation similarity between two users
- User Based Collaborative consists of two phases:
  #### 1st phase (Pearson Correlation Phase)
  - Find Similarity between the target user with all other remaining users.
  #### 2nd phase (Recommendation Phase)
  - Recommending web series to the target user which is most similar to the remaining users.

- Create a function to find seen web series and unseen web series to the target user.
- Create a function to give recommendations.


#### Note
This algorithm is useful when the number of users is less. Its not effective when there are a large number of users and it will become computationlly expensive. To overcome this probem there is an algorithm which is less expensive than User Based Collaborative Filtering and i.e. <b>Item Based Collaboraive Filtering</b>. To know more please click:
https://github.com/IshanSingh611/Item-Based-Collaborative-Filtering

and to know more about the <b>COLD START PROBLEM</b>, please click: https://github.com/IshanSingh611/Popularity-Based-Recommendation-System-User-Cold-Start-Problem
  
  
 


 
