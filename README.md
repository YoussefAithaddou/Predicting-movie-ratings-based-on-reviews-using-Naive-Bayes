# Predicting-movie-ratings-based-on-reviews-using-Naive-Bayes

* Scraped over 500 pages of reviews and ratings from RotenTomatoes.com for the movie Mortal Kombat 2021 using python and selenium.
* Cleaned and converted data into a matrix of token counts with the help of sklearn's CountVectorizer.
* Optimized Naive-Bayes multiclass classifier using GridsearchCV to choose the optimal parameters.
* Classified data and predicted the movie ratings based on the written reviews.

# Resources Used
* Python Version: 3.7
* Packages: pandas, numpy, sklearn, matplotlib, seaborn, selenium.
* ChromeDriver 95.0.4638.10 [download](https://chromedriver.chromium.org/downloads).
# Web Scraping
* Used selenium to extract 1000 rating and review od RotenTomatoes's users.
* For simplification reasons, I considered half stars as full stars. That is, for example, a 4.5 rating is considered 5.0 rating.
# Data visualization
* The data extraction process gives the following results:
  1. Reviews: written critic of users.
  2. Stars: from 1 to 5 where 5 is the maximum possible value.
![image 1](https://github.com/YoussefAithaddou/Predicting-movie-ratings-based-on-reviews-using-Naive-Bayes/blob/main/Movie%20reviews.PNG)
![image 2](https://github.com/YoussefAithaddou/Predicting-movie-ratings-based-on-reviews-using-Naive-Bayes/blob/main/Histogram.png)


# Classification results
Using the Naive Bayes Classifier the following results:

![Classification report](https://github.com/YoussefAithaddou/Predicting-movie-ratings-based-on-reviews-using-Naive-Bayes/blob/main/classification_report.PNG)
![Heat map](https://github.com/YoussefAithaddou/Predicting-movie-ratings-based-on-reviews-using-Naive-Bayes/blob/main/Heatmap.png).

