# Neural-Network-based-Breast-Cancer-Classification-Model
Build a predictive system using Neural Network to classify whether the Breast tumor is benign or malignant.
![benign-vs-malignant-tumors-364765-640x360](https://github.com/harshitah2s4/Machine-Learning-Project-for-Breast-Cancer-Classification/assets/101599002/262200c1-ead0-44f6-b648-fe625e9cc4f6)

***Steps Followed-***

**Importing the required Dependencies-**
Importing all the required libraries for our model.

**Data Collection and Pre-processing-**
We have loaded the dataset from sklearn library and then we have loaded the data into the dataframe.We find no column contains missing values.After checking the distribution of Target Variable we find that 357 samples are benign and 212 are malignant.

**Separating the features and data-**
We get the insight all the parameters are slightly higher for malignant than benign cases.

**Splitting the data into training data & Testing data-**
Here we have splitted the x and y values

**Standarising the data-**
After splitting the data , we have to standarise the data using StandardScaler() function to increase accuracy score.

**Building the Neural Network-**
Tensorflow and Keras libraries were imported, then after setting up and compiling the layers of Neural Network, it was trained by model.fit() function and the accuracy turned out to be 
94.87%.

**Accuracy of the model on test data-**
model.predict()function is used to give prediction probability of each class for that data point.

**Building a prective system-**
This is the last step . This gives the result whether the tumour is benign or malignant.

