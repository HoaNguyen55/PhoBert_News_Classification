# PhoBert_Sentiment_Classification
## Summary:
### Dataset:
+ train.txt
+ In case that you want to split dataset, you can use ***"train_test_split"*** function to divided to two subset, 80%-90% training set and the rest for testing set
### Input/Output:
- **Input**: A Vietnamese paragraph is less than 256 words
- **Output**: A related topic
### Run:
- Step 1: Open file PhoBert-News.ipynb
- Step 2: Mount disk with Google Colab and create new folder
- Step 3: Change directory folder
- Step 4: Import library and install some packages, initialize BERT model with pretrained is PhoBert
- Step 5: Load dataset and split 90% for training, 10% for validate
- Step 6: Training BERT model and plot loss and accuracy with (number of epoch * 5), where 5 is the number of time saved model (e.g ~500 steps, every 100 steps saved model ...)
- Step 7: Print classification report
- Step 8: Predict a paragraph
## Contact:
Email: hoanlmbd@gmail.com
