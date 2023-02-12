# Dataset for Social Media Toxic Comments Text Classification

Please upload the following datasets into your Google Drive before running Toxic_Comments_Text_Classification.ipynb on Google Collab.

Dropbox Link to Download Dataset: https://www.dropbox.com/s/o7armbjoyo7h4g4/Dataset.zip


| S/No |          File Name          |                                                                                File Description                                                                                        |
|:----:|:----------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1    | toxicity_parsed_dataset.csv | Medley Data -  Toxicity Dataset                                                                                                                                                        |
| 2    | X_train.pickle              | - Train set of vectorised text data using 60% to 40% (train-test split)<br><br>- Text data is the “Text” column from Toxicity Dataset, vectorised using DistilBERT word embedding      |
| 3    | X_val.pickle                | - Validation set of vectorised text data using 60% to 40% (train-test split)<br><br>- Text data is the “Text” column from Toxicity Dataset, vectorised using DistilBERT word embedding |
| 4    | y_train.pickle              | Corresponding Oh_Labels for X_train data                                                                                                                                               |
| 5    | y_val.pickle                | Corresponding Oh_Labels for X_val data                                                                                                                                                 |
| 6    | ytcomments.csv              | Comments and respective toxicity label scraped from YouTube video                                                                                                                      |