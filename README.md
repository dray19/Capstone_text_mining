# Capstone_text_mining
Code from capstone project done in Master program. 

“Capstone_NLP_EDA.ipynb” is code for exploratory data analysis on reviews from the yelp dataset we found online. There were just over a million reviews that were analyzed. Also, in this file there is prediction of sentiment using stars from yelp reviews as the dependent variable.

“Creating_lexcion.ipynb” is code used to create a domain specific lexicon for sentiment of reviews from Accommodation and Food Services category in the yelp data set. Steps are shown on how the lexicon was created. Also, results from how the lexicon created performed on classifying the sentiment of the review can be seen. These are the best results from many different lexicons created. Each polarity score from all reviews was scaled between 0 to 100. And the mean score was taken for all reviews to see how negative or positive the reviews were for this domain. 

‘True Model.ipynb” is code that follows the same steps as “Creating_lexcion.ipynb” but used a different way of evaluating the domain specific lexicon method. One test was with data that was an unbalance dataset of mostly positive reviews. The second test was the same dataset but the positive reviews were under sampled to balance the dataset. Both of the test created lexicons using the train data and then tested on how well it classified the reviews using the test dataset.  

“yelp_LDA.ipynb” is code for a different way of predicting if a review is negative or positive. Instead of using countvectorizer or tfidfvectorizer to predict, the independent variables are the topic distributions from the LDA model. The dependent variable was the review stars. This method did great on the train data but didn’t do great on the new data. 
 
 Also, the PowerPoint of the project in greater detail is attached.
