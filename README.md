# Customer-Churn-Modeling
Build customer churn model based on customer past behavior.

## Library
In this analysis, several packages will be used to assist us in conducting data analysis,

1. Pandas (Python for Data Analysis) is a Python library that focuses on data analysis processes such as data manipulation, data preparation, and data cleaning.
    a. read_csv() is used to read csv files
    b. replace() is used to replace the value
    c. value_counts() is used to count unique from column
    d. drop() is used to remove
    e. describe() is used to view the description of the data
    f. value_counts() is used to count unique from column

2. Matplotlib is a Python library that focuses on visualizing data such as plotting graphs. Matplotlib can be used in Python scripts, Python and IPython shells, web application servers, and several other graphical user interface (GUI) toolkits.
    a. figure() is used to create a new figure
    b. subplots() is used to create an image and a set of subplots
    c. title() is used to give a title to the image
    d. ylabel() is used to label the Y-axis of the image
    e. xlabel() is used to label the Y axis of the image
    f. pie() is used to create a pie chart

3. Seaborn builds plots on top of Matplotlib and introduces additional plot types. It also makes your traditional Matplotlib plots look prettier.
    a. countplot() is used to create a plot with the number of observations in each bin of the categorical variable
    b. heatmap() Plot rectangular data as a color-encoded matrix

4. Scikit-learn is a library in Python that provides many Machine Learning algorithms both for Supervised, Unsupervised Learning, or used to prepare data.
    a. LabelEncoder() is used to change the value of a variable to 0 or 1
    b. train_test_split() is used to split data into 2 row sections (Training & Testing)
    c. LogisticRegression() is used to call Logistic Regression algorithm
    d. RandomForestClassifier() is used to call the Random Forest Classifier algorithm
    e. confusion_matrix() is used to create a confusion matrix
    f. classification_report() is used to create a classification report, which includes the accuracy of the model

5. Xgboost is a library in Python for the extreme gradient boosting (xgboost) algorithm.
    a. XGBClassifier() is used to call the XG Boost Classifier algorithm

6. Pickle implements a binary protocol for serializing and de-serializing Python object structures.
    a. dump() is used to store
