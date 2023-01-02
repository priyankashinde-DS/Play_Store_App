# Play Store App Review
Exploratery Data Analysis

# Problem statement
## Explore and analyze the data to discover key factors responsible for app engagement and success.

## Project approach
I decided to move ahead with the project in 5 steps as breaking down a problem is very important. It provides us the analysis of different variables of data and relations among them.

**1.Understanding the problem:** Analysing the problem is very importent because output from the data is mainely depends upon which questions are asked to the data.For getting desired output or insights from the data,we need to ask right questions.

**2.Analysis of Data Set:** Analyzing the given dataset, checking its sanity and then proceeding with further analysis. After being comfortable with the dataset; we explored the various columns and their trends if any.

**3. Visualization :** A picture is worth 1000 words, taking it seriously and tried to explain relation among variables by different types of visualization techniques.

**4.Feature Selection:** Selecting only those features which is most importent for finding out correct insights from the data set.

**5.Conclusion:** In last step summing up results and came up with the inferences and recommendations.

# Play Store Applications Dataset

![image](https://user-images.githubusercontent.com/87980985/210269652-caf2f377-64a2-4091-a7cc-259174321af0.png)

# Data visualization

##  **Installs** 
  This feature shows how many times an application has been downloaded from the Google Play Store.
  
  ![image](https://user-images.githubusercontent.com/87980985/210270704-62dd5891-0bd3-4f18-8fff-68442a5bf6c0.png)
  
The above figure gives us the impression that the applications have been downloaded at least once and at maximum more than one billion times.
The most number of applications are with over 1 million and less than 5 million installs.
There are **only 20 applications in Big Billion Club.**

## **Top Category & Genres with Rating**

![image](https://user-images.githubusercontent.com/87980985/210270956-0a5458d7-d96a-482b-b10b-0dc7a4e9cdf0.png)

**Gaming** category is clearly at the top of the chart with most installations and an average rating of 4.25.
Communication just falls short of Game in terms of installations and is ranked second in the most installed category.

![image](https://user-images.githubusercontent.com/87980985/210271106-73b31e1c-ced5-470e-830b-4e41c31cc7b9.png)

Genres are the sub categories of the feature category so there few categories are divided into the genres and some are not.
From the feature category we have seen that "Communication" is at second place but in genres it's top the chart because "Communication" have only one genre that is "Communication" itself but in the case of categry "Game" it is divided into many genres.
Genres doesn't seems to have lot of impact on user's dicision making as it only the sub part of category.

## **Application type**

![image](https://user-images.githubusercontent.com/87980985/210271299-54be0f5d-ea5e-4089-bbec-490ee643c1a4.png)

it's clearly visible that there are maximum number of Free applications in the data set ,which is about 92.6 % of total applications.

## **Content rating**

![image](https://user-images.githubusercontent.com/87980985/210271504-4cda1fc5-a51e-41c1-8c60-50efa693ac64.png)

We observe significant relationships between the Install and Contain Rating in the above plots.Applications with content rating type "Everyone", "Everyone 10+" and "Teen" have the most installations, with an average rating exceeding 4.2.
"Everyone" have the most number of counts and installations,followed by "Teen".

## **Android version**

![image](https://user-images.githubusercontent.com/87980985/210271653-2d9a5f84-c479-472c-a835-31ebb35e80b0.png)

Android Version "Varies with device " has the most number of total installs and permitted android minimum version which started with release version 4 has appeared in the chart most.
Android Version "Varies with device " has the most number of total installs because Google Play allows developers to upload multiple APKs for the same app and user get freedom to download APKs according to device's version.
Applications which permitts short range of applications version , applications which permitts only latest android versions have less installs.

## **Correlation**

![image](https://user-images.githubusercontent.com/87980985/210271736-6151ea30-0a28-4056-88ff-3c04eee3e386.png)


1.Reviews have highest Positive Correleation with Installs with correlation value of +0.62.
It Shows that as the number of installations increased,the number of reviews also increases.
2.Price is only variable which have Negative Correleation between with the Installs with correleation value of -0.0097.
This indiacates as the price of appliaction decreases,the number of installations increases.
1.Rating also Negatively correlated with the Price with correlation value of -0.021.
Higher priced get low rating with compared to low priced appliactions.


# User reviews dateset

![image](https://user-images.githubusercontent.com/87980985/210269852-a5b3ee3e-85a3-48cd-9af0-e0d5710b1dd4.png)


## **Sentiment**
**1. Positive 😍

**2. Negative 😠

**3. Neutral 😑

![image](https://user-images.githubusercontent.com/87980985/210271797-b5cdae00-b5fa-43bf-99eb-c1f852d2b2ec.png)

## **Sentiment analysis**

![image](https://user-images.githubusercontent.com/87980985/210271883-a8097c81-be81-45dd-8bba-feef656c22a3.png)

The mean of subjectivity is 0.50 and 50 % of subjectivity values lies between 0.35 to 0.65.
According to standard practices, 0.50 is a good subjectivity score, and we will not discard the values with higher subjectivity, since the mean subjectivity score for data is 0.492770..
The mean value of sentiment polarity is 0.182171 and 50% of the values lie between 0 and 0.40, for this reason 64.00 % of sentiments are positive.

# CONCLUSION

1.Because the average rating for an application is 4.17, and most applications get between 3.8 and 4.5 ratings, it is hard to determine an application's success solely based on its rating.

2.The number of installations is a very good indicator of an app's success and engagement. Only twenty apps have more than 1 billion installations.

3.From the data it's clearly visible that User's like to install Free applications.Approximately 93% of the apps in the Google Play Store are free to download, and the price is negatively correlated with both installs and ratings.

4.Small sized applications are installed more, but for higher installed applications amounts, big sized apps are also more prevalent.

5.Even though category GAME has the highest total installs, category COMMUNICATION is the most successful category due to the highest average installs, higher percentage of positive sentiment, and six apps with more than billion installs compared to just one app from category GAME.

6The Top apps according to Installs and Positive Sentiment's percentage fall under content rating EVERYONE and Android version VARIES BY DEVICE, suggesting users like freedom.

7.App's updated at latest have the highest installs and good rating,which indicates user's tends to download app's which are latest.

8.Positive sentiment's for app's under the category HEALTH_AND_FITNESS are the highest.

9.About 63% of sentiments are positive and the Top 10 categories also have a positive sentiments percentage around 60%, except GAME which has a 56% positivity rate..

### Using this project, we examine the factors that determine a user's decision to download an app, and the factors that determine its success and enrolment.
