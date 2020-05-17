[Exploratory Analysis Of Kickstarter Data](https://github.com/sumitkumar-00/Data_Science_Projects/blob/master/kickstarter.ipynb)
 - Kickstarter is an American public benefit corporation based in Brooklyn, New York, that maintains a global crowdfunding platform focused on creativity <br>
 - The company's stated mission is to "help bring creative projects to life" <br>
 - As of December 2019, Kickstarter has received more than $4.6 billion in pledges from 17.2 million backers to fund 445,000 projects
 
 Analysis Objective:
 - We want to be able to provide recommendations to project teams seeking to raise funds using crowfunding on Kickstarter
 - What is the best length of time to run a campaign?
 - What is an ideal pledge goal?
 - What type of projects would be most successful at getting funded?
 - Is there an ideal month/day to launch a campaign?
 
[Plot Based Movie Recommender](https://github.com/sumitkumar-00/Data_Science_Projects/blob/master/plot_based_movie_recommender.ipynb)

The dataset is from [Open Movie Database](http://www.omdbapi.com/). It was downloaded from their website using the APIs provided. We have roughly 65K movies and their attributes such as rating, vote count and actors etc.
 
Objective:
 - Build a plot based movie recommender that recommends movies based on a similarity score of plots
 - User inputs a movie name and similar movies based on similarity score are recommended
 
 [Police Stops in Austin, TX](https://github.com/sumitkumar-00/Data_Science_Projects/blob/master/austin_tx_police.ipynb)

This is an exploratory data analysis for police stops in Austin, TX

[Cat and Dog Image Classification with Image augmentation(convnet)](https://github.com/sumitkumar-00/Data_Science_Projects/blob/master/cat_and_dog_Image_Augmentation.ipynb)

This is a classification model (convnet) to classify pictures of dogs and cats with image augmentation. 4k pictures of dogs and cats each were used for training. Test set had 1k pictures for each class. The model achieved accuracy of 85%. This is an improvement of almost 7% over my model without image augmentation.

[Credit and Genre Based Movie Recommender](https://github.com/sumitkumar-00/Data_Science_Projects/blob/master/credit_based_mr.ipynb)

The dataset is from [Open Movie Database](http://www.omdbapi.com/). It was downloaded from their website using the APIs provided. We have roughly 65K movies and their attributes such as rating, vote count and actors etc.
 
Objective:
 - Build a credit based movie recommender that recommends movies based on a similarity of Genre, Directors and Actors
 - User inputs a movie name and similar movies based on similarity score are recommended

[Predicting IRIS Species](https://github.com/sumitkumar-00/Data_Science_Projects/blob/master/iris.ipynb)

IRIS dataset was split in 80/20 for training and testing respectively. Each of Logistic Regression, KNN and RandomForest models achieved 96.67% accuracy in predicting species of the iris flower

[Image Classification for numerals (MNIST)](https://github.com/sumitkumar-00/Data_Science_Projects/blob/master/mnist.ipynb)

This is a simple convnet model using Keras and tensorflow as backend to classify handwritten numerals. Accuracy is 97.87% for this model

[Cat and Dog Image Classification (convnet)](https://github.com/sumitkumar-00/Data_Science_Projects/blob/master/cat_and_dog.ipynb)

This is a classification model (convnet) to classify pictures of dogs and cats. 4k pictures of dogs and cats each were used for training. Test set had 1k pictures for each class. The model achieved accuracy of 77%. Data augmentation probably can be used to improve accuracy. That's a project for some other day

[Basic Movie Recommender](https://github.com/sumitkumar-00/Data_Science_Projects/blob/master/basic_movie_recommender.ipynb)

DataSet:
This dataset is from Open Movie Database
It was downloaded from their website using the APIs provided
We have roughly 65K movies and their attributes such as rating, vote count and actors etc.

Objective:
Build a basic movie recommender that recommends movies based on a score
The score for a movie is calculated based on number of votes and the ratings
Higher score translates to higher recommendation

P.S. : I am working on a more complex movie recommender and it will be uploaded soon.

[Classifying credit data into defaulters/non-defaulters](https://github.com/sumitkumar-00/Data_Science_Projects/blob/master/credit_default.ipynb)

This dataset contained 3 predictors ( student, balance and income) and one reponse default/no default. Dataset is imbalanced and only 3 percent of the 10K observation belong to default class. Randomforest classifier was able to achieve an area under curve equal to 0.89

[Credit Card Fraud Detection](https://github.com/sumitkumar-00/credit-card-fraud-detection)

This dataset is from Kaggle. It contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

GradientBoostingClassifier was able to achieve an AUC of 0.98
