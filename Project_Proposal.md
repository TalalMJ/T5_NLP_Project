# Hotel Reviews Natural Language Processing

![Greece_Hotel_Acropolis_Congress2020](https://user-images.githubusercontent.com/93079224/146894109-7bd53610-0918-4cf0-94d2-6a4377b7405d.png)


# Introduction
Client reviews are a crucial part of improving hotels and customers experience and travel plans.Customers reviews plays an important part for hotel improvement and in order to improve their services. In this project the purpose is to build a Natural Language Processing model that predicts whether the review is positive or negative.

The goal of this project is to help hotels acknowledge the majority of reviews and determine their customers feedback to improve hotel services and customers experience.



# Data Description
We will take the data from [Kaggle](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe). 
The dataset contains over 500k reviews and scoring of more then 1k luxury hotels.
| Field Name | Description                                                                                                                                       |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------|
|Hotel Address| Address of hotel.                                                                                                                                |
|Review Date| Date when reviewer posted the corresponding review.                                                                                                |
|Average Score| Average Score of the hotel, calculated based on the latest comment in the last year.                                                             |
|Hotel Name| Name of Hotel|
|Reviewer Nationality| Nationality of Reviewer                                                                                                                    |
|Negative Review| Negative Review the reviewer gave to the hotel. If the reviewer does not give the negative review, then it should be: 'No Negative'
|Review Total Negative| Total number of words in the negative review.|
|Positive Review| Positive Review the reviewer gave to the hotel. If the reviewer does not give the negative review, then it should be: 'No Positive'|
|Review Total Positive| Total number of words in the positive review.|
|Reviewer Score| Score the reviewer has given to the hotel, based on his/her experience|
|Total Number of Reviews reviewers given| Number of Reviews the reviewers has given in the past.|
|Total Number of Reviews| Total number of valid reviews the hotel has.|
|Tags| Tags reviewer gave the hotel.|
|Days since review| Duration between the review date and scrape date.|
|Additional Number of Scoring| There are also some guests who just made a scoring on the service rather than a review. This number indicates how many valid scores without review in there.|
|lat| Latitude of the hotel|
|lng| longtitude of the hotel|

# Tools
* Technologies: Python, Jupyter notebook.
* Libraries: NLTK, Seaborn, Matplotlib, SQLAlchemy, NumPy, Pandas, Sklearn.



