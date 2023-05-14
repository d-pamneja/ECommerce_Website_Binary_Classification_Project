# E-commerce Shopper's Behaviour Understanding
## Understand the online shopper purchasing pattern through Machine learning

### Description of Problem Statement
Assume that you are working in a consultancy company and one of your client is running an e-commerce company. They are interested in understanding the customer behavior regarding the shopping. They have already collected the users’ session data for a year. Each row belongs to a different user. The “Made_purchase” is an indicator that whether the user has made a purchase or not during that year. Your client is also interested in predicting that column using other attributes of the users. The client also informs you that the data is collected by non-experts. So, it might have some percentage of error in some columns.

### Evaluation Metric 
The evaluation metric for this competition is [Mean F1-Score](https://en.wikipedia.org/wiki/F-score). The F1 score, commonly used in information retrieval, measures accuracy using the statistics precision. The F1 metric weights recall and precision equally, and a good retrieval algorithm will maximize both precision and recall simultaneously. Thus, moderately good performance on both will be favored over extremely good performance on one and poor performance on the other. ## Submission Format The file should contain a header and have the following format

## Model Used
Here, I have used the Voting Stacking Classifer, which consists of Gradident Boosting Classifier and Perceptron Algorithm. Using that, I have obtained a final score of 0.6454 on the test set. 