# Bankruptcy-Detector
<br>
<br>
Bankruptcy is an important issue that many banks have to deal with on a constant basis. Many long-time defaulters end up paying getting more loans due to the lack of a method to detect bankruptcy in account holders. Our project utilizes machine learning in order to create an efficient and automatic process to detect signs leading to bankruptcy in account holders. This will help many banks secure funds and detect early signs of bankruptcy so funds can be withheld and major losses can be prevented. Our project will be able to automatically assess account information from banks and provide banks relevant information about bankruptcy signs it has detected.
<br>
<br>
METHODOLOGY
<br>
<br>
1. Obtain the company bankruptcy dataset from kaggle.
<br>
2. Pre processing and cleaning the dataset to make sure results are optimal.
<br>
3. Splitting the Dataset into training and testing.
<br>
4. Training the dataset on the mentioned algorithms such as ANN, KNN & Random  Forest.
<br>
5. Comparing Accuracy of produced results.
<br>
<br>
DATA PREPROCESSING
<br>
<br>
A lot of preprocessing was necessary as the dataset contained a lot of features that were not correlated highly to the bankruptcy and hence had to be removed completely from the dataset.
The dataset was highly uneven and as a result it had to be oversampled to make the minority classes at par with the majority one.
Once all these issues were solved with the dataset we were able to successfully start running the algorithms so we can proceed with accuracy comparison.
As mentioned above , dataset had various types of issues that had to be dealt with before training it on the concerned algorithms.
It’s always a good habit to check for null values inside a dataset. This is done to understand the dataset more clearly and replace these with either average of that entire feature. However in certain cases when the amount of null values inside a feature are comparatively less , the particular row which has those null values can be dropped from the dataset provided a lot of information is not lost along with it.
Another issue which we came across in the dataset was that there were multiple features which were highly un-correlated to the label (“Bankrupt?”). In order to fix this , these concerned parameters were removed from the dataset. Once the parameters were dropped , the unevenness of the dataset was checked. It has been seen that uneven dataset punish the minority class to a great extent and as a result oversampling was used.
As a result the entire procedure of cleaning the dataset is extremely important and is commonly called as data engineering or data cleaning
<br>
<br>
CONCLUSION
<br>
<br>

• After studying the comparison, it was thus seen that Random forest dominated the other two algorithms with an overall accuracy of 98%.
<br>
•KNN was also able to provide us with a good overall accuracy of 96%.
<br>
• ANN was not able to give us an accuracy which was at par with its other two counterpart algorithms since it only gave us an overall accuracy of 90 % which is also a good overall accuracy in itself.
<br>
• As a result, we can conclude that the random forest model can be used for the real world predictions.
<br>
<br>

