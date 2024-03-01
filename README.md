<h1 align="center"> Play Store App Review Analysis</h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter </a> </h5>

<p align="center"> 
<img src="GIF/google play.gif" alt="Animated gif" height="282px">
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### Input Files:
  <li><b>Play Store Data.csv</b> - It contains the basic details of the app like number of user reviews, ratings, etc.</li>
  <li><b>User Reviews.csv</b> - It contains the user reviews and its sentiment score for the respective app.</li>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📖 Introduction:
In this project, we aim to analyze a dataset containing information on 10,841 Play Store applications, along with user reviews. The focus is on understanding the factors influencing an app's popularity, pricing, size, and user sentiments. The dataset includes categories like family, communication, entertainment, tools, music, and camera. By exploring and analyzing this data, we aim to identify key insights that contribute to app engagement and success. The Play Store data consists of 10841 rows and 13 columns, while the user review data has 64295 rows and 5 columns. Our approach involves filtering the data and creating plots to facilitate a comprehensive Exploratory Data Analysis (EDA). The ultimate goal is to gain valuable insights for app designers to maintain their market position in the dynamic mobile app landscape.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
### The contents of Play Store Data are:
* App: It contains the name of the app with a short description (optional).
* Category: This section gives the category to which an app belongs. In this dataset, the apps are divided among 33 categories.
* Size: The disk space required to install the respective app.
* Rating: The average rating given by the users for the respective app. It can be in between 1 and 5.
* Reviews: The number of users that have dropped a review for the respective app.
* Installs: The approximate number of times the respective app was installed.
* Type: It states whether an app is free to use or paid.
* Price: It gives the price payable to install the app. For free type apps, the price is zero.
* Content rating: It states which age group is suitable to consume the content of the respective app.
* Genres: It gives the genre(s) to which the respective app belongs.
* Last updated: It gives the day in which the latest update for the respective app was released.
* Current Ver: It gives the current version of the respective app.
* Android Ver: It gives the android version of the respective app.

### The contents of User Reviews are:
* App: It contains the name of the app with a short description (optional).
* Translated_Review: It contains the English translation of the review dropped by the user of the app.
* Sentiment: It gives the attitude/emotion of the writer. It can be ‘Positive’, ‘Negative’, or ‘Neutral’.
* Sentiment_Polarity: It gives the polarity of the review. Its range is [-1,1], where 1 means ‘Positive statement’ and -1 means a ‘Negative statement’.
* Sentiment_Subjectivity: This value gives how close a reviewer’s opinion is to the opinion of the general public. Its range is [0,1]. Higher the subjectivity, closer is the reviewer’s opinion to the opinion of the general public, and lower subjectivity indicates the review is more of a factual information.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📋 Conclusion:
Most of the apps are free so developers should focus on creating free apps to have a huge customer base. If developing paid apps then apps size should not be greater than 40mb. More Apps should be in the category like Events,Beauty,Parenting as they have not been explored much but still quite popular with huge installations. In order to retain the customer base apps should be updated regularly Developers should develop apps such that their content is available for everyone. Bulky apps should be developed in the category like Game, Family. If developing paid apps then its price should not be high and size should be less than 20mb. Apps belonging to Game and Family Category have high negative reviews therefore they should be developed carefully. Like this there can be a lot of conclusions but we have tried to cover the most important ones.
These are some of the aspects that the developer should research before proceeding with the app development. By conducting a simple exploratory data analysis (EDA) on the play store dataset, we not only eliminate avoidable risks of failure, but we may also be able to provide better ideas for building the app.
*	Percentage of free apps = ~92%
*	Percentage of apps with no age restrictions = ~82%
*	Most competitive category: Family
*	Category with the highest number of installs: Game
*	Category with the highest average app installs: Communication
*	Percentage of apps that are top rated = ~80%
*	There are 20 free apps that have been installed over a billion times
*	Minecraft is the only app in the paid category with over 10M installs. This app has also produced the most revenue only from the installation fee.
*	Category in which the paid apps have the highest average installation fee: Finance
*	Most popular app in the Play Store based on the number of reviews: Facebook
*	The median size of all apps in the play store is 12 MB.
*	The apps whose size varies with device has the highest number average app installs.
*	The apps whose size is greater than 90 MB has the highest number of average user reviews, i.e., they are more popular than the rest.
*	Helix Jump has the highest number of positive reviews and Angry Birds Classic has the highest number of negative reviews.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


