# Predict_Race_from_census_data
My final project from the Summer ML Course at Cornell through Break Thru Tech AI



In this project, I developed a binary classification Random Forest (RF) algorithm to classify individuals based on their race. Initially, I examined the confusion matrix to understand where misclassifications were occurring. Observing a significant number of false negatives, I decided to optimize the model further by tuning its hyperparameters using a grid search. This process helped me identify the best set of parameters to improve model performance.

Following this, I revisited the distribution of two features I had suspected earlier of contributing to misclassifications. Although I constructed another model after optimizing these features, the improvement was minimal. One of the key challenges was the high rate of false negatives, where the model incorrectly classified people as black when they were not. Attempts to handle this through undersampling made the model's performance worse, highlighting the issues with addressing the distribution issues.

To enhance the model, I analyzed feature importance and retained only the top 20 features. This refined model achieved a 90% accuracy rate. Encouraged by this, I explored whether a multi-class classification approach would yield better results. I created a second data frame, ensuring it matched the first one, and encoded the labels to prepare for the new algorithm. However, the multi-class model did not achieve the same level of accuracy as the binary model.

The next steps involve obtaining or adjusting the dataset to balance the class distributions. My model uses a random split which causes the underrepresented classes to be insufficiently sampled in the training set. This imbalance diminishes the model's ability to predict these classes accurately. This project has illuminated the broader issue of algorithmic bias, where models can inadvertently learn and transmit stereotypes present in the data.

Overall, this project provided valuable insights into the challenges of racial classification in machine learning. Addressing these challenges requires careful consideration of data distribution and continuous efforts to mitigate bias in algorithmic predictions.
