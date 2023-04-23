# Crime-Rate-Prediction-System
Developed a create crime rate prediction model using ML algorithms to predict the crime rate and analyse the crime rate based on previous records. Concepts of Random Forest Classifier and Gradient Boosting Classifier were used to develop the model

Dataset is taken from kaggle.com which had 29 attributes out of which we used 9-10 attributes for training the model.
Link of Dataset:-
https://drive.google.com/file/d/1RTxOt1Q6fbo87xVYoiMVFZBSKp_5olph/view?usp=sharing 

Crimes are the significant threat to the humankind. There are many crimes that happen in regular intervals of time. Perhaps it is increasing and spreading at a fast and vast rate. Crimes happen from small village, town to big cities. Crimes are of different type – robbery, murder, rape, assault, battery, false imprisonment, kidnapping, homicide. Since crimes are increasing there is a need to solve the cases in a much faster way.
Crime prediction and criminal identification are the major problems to the police department as there are tremendous amount of crime data that exist. There is a need of technology through which the case solving could be faster. Through many documentations and cases, it came out that machine learning and data science can make the work easier and faster. The aim of this project is to make crime prediction using the features present in the dataset. The objective would be to train a model for prediction. The training would be done using Training data set which will be validated using the test dataset. The objective would be to train a model for prediction. The training would be done using Training data set which will be validated using the test dataset.



Step 1: Preprocessing 
Given the problem you want to solve, you will have to investigate and obtain data that you will use to feed your machine. The quality and quantity of information you get are very important since it will directly impact how well or badly your model will work. You may have the information in an existing database or you must create it from scratch. In the case of CRPS we have gathered data of recent crimes that took place in Alaska from 2013. 

Step 2: Feature Extraction
Feature extraction is a process of dimensionality reduction by which an initial set of raw data is reduced to more manageable groups for processing. A characteristic of these large data sets is a large number of variables that require a lot of computing resources to process. Feature extraction is the name for methods that select and /or combine variables into features, effectively reducing the amount of data that must be processed, while still accurately and completely describing the original data set. There are various types of feature extractions namely manual feature extraction and algorithmic feature extraction. 
Manual feature extraction is a method of feature extraction by which we get to conclusion by logical cutting down the number of attributes in the model.
Algorithmic feature is a method of feature by which we get to the conclusion after algorithmically or computationally cutting down the attributes in the model.

Step 3: Modeling 
Model preparation is one of the most important step in designing a ML system. There are several models that you can choose according to the objective that you might have: you will use algorithms of classification, prediction, linear regression, clustering, i.e. k-means or K-Nearest Neighbor, Deep Learning, i.e Neural Networks, Bayesian, etc.


Step 4: Training and Testing
Training process of a model can be defined as feeding the data to the model so it can strengthen its predictive nature by analyzing the patterns of input data and output data. Testing process of a model can be defined as letting the data predict the value based on the input data received after it has developed a predictive analogy. Usually 70-30 or 80-20 training testing model is used. The CRPS model uses the 80-20 allocation set for the model.

Step 5: Evaluation
After getting enough fed by the data, check the machine created against your evaluation data set that contains inputs that the model does not know and verify the precision of your already trained model. If the accuracy is less than or equal to 50%, that model will not be useful since it would be like tossing a coin to make decisions. If you reach 90% or more, you can have good confidence in the results that the model gives you. 
