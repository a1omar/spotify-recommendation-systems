# spotify-recommendation-systems
This repo is for CIND820 capstone project building a music recommendation system with spotify.

The project is split up into 5 steps: 

**1. Data Preperation:** This step contains feature description and exploratory data analysis for each feature.

**2. Feature Engineering:** This step contains Normalization and One-hot encoding popularity and years categorical features for each song in the data.

**3. Vectorization:** This step contains the vectorization of the genres feature for each song by using tf-idf then the data is combined to include the normalized data for the numerical features, the one-hot encoded categorical features and the tf-idf weights for the genres features all into one dataframe with all the song vectors. Both tf-idf and bag of words were captured at this stage to compare the results at the end. Also non-normalized features were also captured here in order to compare see if normalizing the numerical features would yield greater results.

**4. Vector Similarities:** This step contains cosine similariy, euclidean distance and manhattan distance with the songs in a given user playlist with the dataframe of all the song vectors from the vectorization step. 

**5. Generate Recommendations:** Here we finally have a dataframe with the top n recommendations.
