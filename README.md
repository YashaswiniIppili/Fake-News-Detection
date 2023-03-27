# Fake-News-Detection
This is my first ML based project. I've tried classifying the user input's news into fake or real. </br>
Please download the required datasets from here : https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset </br>

### Working of my model

1. Import the required libraries.
2. The basic idea being merging two datasets (true and fake) and shuffling them. 
3. We add a new column field called "label" to tell if the article is true or fake.
4. Concatenate the two dataframes into one called "data".
5. TfidfVectorizer() is used to convert the text into numerical features.
6. And then we split the data into training and testing using "train_test_split()" with 20% being used for testing.
7. Using Naive Bayes classifier on the training data.
8. We make predictions using the "predict()" method.
