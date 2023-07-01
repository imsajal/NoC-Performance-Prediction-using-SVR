Use any python editor like google collaboratory, jupyter, pycharm etc. for executing the python code.

Following are the steps to achieve prediction-

(Opening the file in google collaboratory, run the code cell by cell)

Step 1- Open the file SVR_NoCs.py in editor.

Step 2- Uploading dataset
        In function pd.read_csv('xyz.csv', encoding='utf-8'), in place of xyz.csv replace with the filename of dataset. 

Step 3- Split the dataset by running up the code present in file.

Step 4- Execute GridSearchCv function present in the file. print(grid.best_estimator_), it will return the best hyperparameters. Use these values in the SVR function present in file and execute the cell. Upon doing this SVR will be trained on the training dataset splitted earlier.

Step 5- Predicted values on testdata, mean square error and SVR time is obtained by simply running the python code present after the SVR function.

