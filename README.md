# ML-fruit-knn-classifier

This simple project demonstrates the prediction of fruits with KNN_algorithm.

step1 : Make dataset by examining the features of fruits say apple i.e. mass,height,width,color etc this acts as feature extraction
step2 : read the csv dataset
step3 : use train_test_split to train the model with 75:25 dataset. 75% for training , 25% for testing.
        X_train : the description of features of fruits
        y_train : the label that acts as parameters to predict
        X_test : the description of features of fruit that is not known by computer
        y_test :  label that acts as parameters to predict (not knwon by computer)
step4 : import KNeighborsClassifier from sklearn.neighbors
Step5 : perform fit (train data) and score (test data)


Note: X_train,y_train data can be accessed by computer
