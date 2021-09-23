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
* The data extraction process gives the following results:
  1. Reviews: written critic of users.
  2. Stars: from 1 to 5 where 5 is the maximum possible value.




# Data visualization

# Classification results
The cleveland heart disease dataset includes 14 different physiological attributes that can indicate the existence of heart disease, these attributes are:
* age
* sex
* chest pain type (4 values)
* resting blood pressure
* serum cholestoral in mg/dl
* fasting blood sugar 
* resting electrocardiographic results (values 0,1,2)
* maximum heart rate achieved
* exercise induced angina
* oldpeak = ST depression induced by exercise relative to rest
* the slope of the peak exercise ST segment
* number of major vessels (0-3) colored by flourosopy
* thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
* Target: 0 = neagtive; 1 = positive

Using the k-fold cross validation algorithm I chose the paramter k of the k_nearest algorithm as k=19. This yields the following results:

![Classification report](https://github.com/YoussefAithaddou/Heart-Disease-Classification-using-The-K-Nearest-Neighbours/blob/main/Classification%20report.PNG)

# Data Visualization
I used Seaborn libraray to plot different pairwise attributes in the testing dataset, especially the age, chest pain type, resting blood pressure, serum cholestoral, maximum heart rate achieved and the oldpeak [Figure 2](https://github.com/YoussefAithaddou/Heart-Disease-Classification-using-The-K-Nearest-Neighbours/blob/main/Data%20Visualization.png). ALso, I created an interactive plot to illustrate the relation between maximum heart rate achieved, resting blood pressure and the serum cholestoral in mg/dl [Figure 3](https://github.com/YoussefAithaddou/Heart-Disease-Classification-using-The-K-Nearest-Neighbours/blob/main/Data%20Visualization%202.PNG).

![Figure 2](https://github.com/YoussefAithaddou/Heart-Disease-Classification-using-The-K-Nearest-Neighbours/blob/main/Data%20Visualization.png)
![Figure 3](https://github.com/YoussefAithaddou/Heart-Disease-Classification-using-The-K-Nearest-Neighbours/blob/main/Data%20Visualization%202.PNG)
