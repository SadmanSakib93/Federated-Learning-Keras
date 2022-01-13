# Federated Learning Keras
- Replace your own dataset file as the dataset.csv. 
- Note that, the sample dataset.csv file I used, it has its labels (Y) in the first column named as "label". The 2nd to nth columns are the features (X). You might want to change the code according to your dataset structure to ensure proper feature and label handling

Following is a sample dataset structure that the program expects:
![image](https://user-images.githubusercontent.com/27827295/149410524-feb98dee-ad42-4966-9223-4b1ae8b943d2.png)

- So, basically, the first column is your class label (defined as "label"). The rest of the columns are your dependent features of the dataset. For example, in this picture, there are 20 features denoted as A1 to A20. Note that, all the features are numerical features in the CSV file. If you have some categorical features, you have to perform One hot encoding/Label encoding to make them numbers, and then after you can run the program! Hope this helps.



## This is a sample Keras implementation of the Federated Learning (FL) for experimental research simulations and might need further modifications to implement it in real-life scenarios.
