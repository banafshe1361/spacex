# SpaceX 
# SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the  savings is because SpaceX can reuse the first stage. This dataset includes details about every launch and its landing outcome.
# This project was given to us in the data science course I  took,but I think you can find this project in Kaggle
# In this project, I first imported the required libraries such as Pendas, numpy, Seaborn and Matplatlib, and then I imported all the models that are supposed to  help in optimizing the prediction.
# Models used:GridSearchCV,LogisticRegression,SVC,DecisionTreeClassifier and KNeighborsClassifier
# Sometimes it is necessary that we create the function and then call it, so we will create a function called plot and confusion matrix so that we can view any of the models in the form of a plot.
# Well, the next step is to standardize the dataset, because our dataset is not in the right scale, and if we do not standardize, our models will encounter an error
# After standardization, we must create a new dataset and then train the models
# We had made two lists named accuracy and method, now we will print them to show the models along with their accuracy values
# We use PLT to make a 10 x 5 box and Bar Plot to show us the accuracy values of all the models we used.
# In the ROC chart, we examine the ratio of X axis and Y axis together
