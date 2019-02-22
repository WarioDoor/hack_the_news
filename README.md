# hack_the_news
Hack the news Datathon https://www.datasciencesociety.net/datathon/
Team leopards 5th place task 1 and overall
The following code is a review of the code used for the task 1 of the 'Hack the News' Datathon by https://www.datasciencesociety.net/

Find here the dataset https://s3.us-east-2.amazonaws.com/propaganda-datathon/dataset/datasets-v5.zip

Find here the complete article https://www.datasciencesociety.net/datathon-hacknews-solution-leopards/

Approach:
Perform data exploration
Text cleaning (incl. lemmization), removing pronouns and common words
Choose a representation of the sentences 
Find the best learner (KNN, LR, AdaBoost, Random Forests, Gradient Boosting, Decision Tree, MLP) and its hyperparameters

Finidigs
On cleaned text, Logistic Regression with a large number of features outperformed the other learners using 3 ngrams and a weak regularization.

