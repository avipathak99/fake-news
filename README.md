# Fake-news detection using deep learning

This is a jupyter notebook and can be run directly in jupyter

# Problem Statement

​Develop a model to detect if a given news article is a fake one or legitimate(real) one. 

 

# Dataset location

https://www.kaggle.com/c/fake-news/data

 

# About dataset

The dataset consists of 3 CSV files: "train.csv", "test.csv" and "submit.csv".
"train.csv" contains following columns

"id" of article
"Title" of the article
"Text" of the article
"Author" of the article
"Label" of article
1: fake
0: real
"test.csv" contains the same attributes as "train.csv", but without the "label" attribute. Prediction is to be performed on these articles.

"submit.csv" contains sample submission format. For every article in "test.csv" file, submission CSV file should have two columns: `id` and `label`. The `id` column should refer to a row in the "test.csv" file, and the `label` column should refer to its label i.e. real (`0`), or fake (`1`).


# Submission

Link to a Source code (Preferably on GitHub)
CSV file containing your result (as described above for submit.csv)
File describing your approach of solving the problem. Include precision and recall for each classes.

# Results
Test accuracy: 0.9884615540504456
Test precision: 0.9948210716247559
Test recall: 0.9827907085418701
