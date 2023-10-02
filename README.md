# ML-fruit-knn-classifier

This simple project demonstrates the prediction of fruits with KNN_algorithm.

step1 : Make dataset by examining the features of fruits say apple i.e. mass,height,width,color etc this acts as feature extraction <br>
step2 : read the csv dataset <br>
step3 : use train_test_split to train the model with 75:25 dataset. 75% for training , 25% for testing. <br>
        X_train : the description of features of fruits<br>
        y_train : the label that acts as parameters to predict<br>
        X_test : the description of features of fruit that is not known by computer<br>
        y_test :  label that acts as parameters to predict (not knwon by computer)<br>
step4 : import KNeighborsClassifier from sklearn.neighbors<br>
Step5 : perform fit (train data) and score (test data)<br>


Note: X_train,y_train data can be accessed by computer
