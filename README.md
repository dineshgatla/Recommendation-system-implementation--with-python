We scrapped the website holidify and then added modifications to it to get the desired dataset as per our requirements.

Exploratory Data analysis
Performing the EDA, we decided to visualize the data to have a better understanding of the dataset.
The analysis and visualization on the dataset are done using the Plotly library because we wanted to make our analysis graphs to be interactive.
Additionally, the data analysis has been divided into various sections to understand the dataset well.

Implementation Classification model
To analyze the data and detect outliers this model was used to check the model parameters and implement the baseline model and also measure its accuracy. 

Implementation of Content model
The Content-Based Recommender works based on the data that we take from the user, by using this data we create a user profile.
This can then used to make suggestions to the user, as the user provides more input or takes more actions on the recommendation thus making the engine more accurate.

Implementation of Recommender clustering
After implementing the cosine similarity model, we tried to implement a content based clustering model where the input features to the model are location name and a short description of the location that we had. 
The diagram below clearly shows the process flow and steps to build a content based recommender system using K-means clustering. 
To begin with the clustering model, we had to choose the accurate value of k for K-means clustering algorithm. The clustering process started with preprocessing the data and modifying it as per requirements.

Implementation of Recommender Surprise
We implemented collaborative filtering for the recommendation system and in this case, the surprise library was used.
Since the system aims to predict user preference on past experience by filtering the users preference on the basis of past habits of similar users.

