# Machine Learning Data Science Bootcamp

This respository is dedicated to what I learned from Daniel Bourke and Andrei Neagoie in this udemy course,
[Complete Machine Learning & Data Science Bootcamp](https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/)


| Number |  Notebook 	|
| :---  | :--- 	|
| 01 | [Heart Disease Classification](https://github.com/MHidayatz/Machine_Learning_Data_Science_Bootcamp/blob/main/end-to-end-heart-disease-classification.ipynb) |
| 02 | [Predicting Sales Price of Bulldozer (Time Series)](https://github.com/MHidayatz/Machine_Learning_Data_Science_Bootcamp/blob/main/end-to-end-bulldozer-price-regression%20_.ipynb) |
| 03 | [SupervisedLearningProject](https://github.com/MHidayatz/Machine_Learning_Data_Science_Bootcamp/blob/main/end_to_end_dog_vision.ipynb) |

### 01. Heart Disease Classification
<hr>
</hr>

This project focus on working specifically on structured data. I wil be tackling it using this 6 step machine learning framework.

1.	Problem Definition: Given clinical parameters about a patient, can we predict if they have heart disease.
2.	Data: The data that we have is found in this link: https://www.kaggle.com/ronitf/heart-disease-uci
3.	Evaluation: If we can reach 95% accuracy at predicting if a patient has heart disease during the proof of concept, we will pursue the project.
4.	Features: There are 14 features available in the dataset, which we will identify which feature are of higher importance.
5.	Modelling: Will be using the following tools, Pandas, Matplotlib, Numpy, SKlearn and Jupyter to build a few machine learning models.
6.	Experiments: Will be experimenting with several machine learning models such as logistics regression, KNN, Random Forest and Catboost for this dataset.

### 02. Predicting Sales Price of Bulldozer (Time Series)
<hr>
</hr>

This project focus on working specifically on structured data. I wil be tackling it using this 6 step machine learning framework.

1.	Problem Definition: Using historical data, I will try to predict the sale price of bulldozer in the future.
2.	Data: The data that we have is found in this link: https://www.kaggle.com/c/bluebook-for-bulldozers/data
3.	Evaluation: The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.
4.	Features: Kaggle provides a data dictionary detailing all of the features of the dataset. You can view this data dictionary in Kaggle. Link: https://www.kaggle.com/c/bluebook-for-bulldozers/data
5.	Modelling: Will be using the following tools, Pandas, Matplotlib, Numpy, SKlearn and Jupyter to build a few machine learning models.
6.	Experiments: Will be experimenting with several machine learning models such as logistics regression, KNN, Random Forest and Catboost for this dataset. Unlike the first project, I will try to improve the model by finding the best hyperparameters using RandomizedSearchCV.

### 03. SupervisedLearningProject
<hr>
</hr>

This project focus on working specifically on unstructured data. I wil be tackling it using this 6 step machine learning framework.

1.	Problem Definition: Identifying the breed of a dog given the image of the dog.
2.	Data: The data that we have is found in this link: https://www.kaggle.com/c/dog-breed-identification/overview
3.	Evaluation: The evaluation is a file with prediction probabilities for each dog breed for each test image.
4.	Some features information about the data:

    * We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
    * There are 120 breeds of dogs (this means there are 120 different classes).
    * There are around 10,000+ images in the training set. (these images have labels).
    * There are around 10,000+ images in the test set. (these images have no labels, because we want to predict them).

5.	Modelling: Will be using the following tools, Pandas, Matplotlib, Numpy, SKlearn, Tensorflow and Google Colab to build a few machine learning models.
6.	Experiments: Will be building a model with the following actions,

    * Takes the input shape, output shape and the model we've chosen as parameters.
    * Defines the layers in a Keras model in sequential fashion (do this first, then this, then that).
    * Compiles the model (says it should be evaluated and improved).
    * Build the model (tells the model the input shape it'll be getting).
    * Returns the model.

