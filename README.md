
# Youtube Adview prediction

A Machine Learning project for ML Internship offered by InternshipStudio.

## Objective

To build a machine learning model which will predict youtube adview count based on other youtube metrics.

## Data Description

* train.csv - the training set.
* test.csv - the test set
* The file train.csv contains metrics and other details of about 15000 youtube videos. The metrics include number of views, likes, dislikes, comments and apart from that published date, duration and category are also included. The train.csv file also contains the metric number of adviews which is our target variable for prediction.

## Attribute Information
* 'vidid' : Unique Identification ID for each video
* 'adview' : The number of adviews for each video
* 'views' : The number of unique views for each video
* 'likes' : The number of likes for each video
* 'dislikes' : The number of likes for each video
* 'comment' : The number of unique comments for each video
* 'published' : The data of uploading the video
* 'duration' : The duration of the video (in min. and seconds)
* 'category' : Category of each of the video