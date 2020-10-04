# Coursera_Capstone
This repository is to share my work for a Coursera project

## Introduction
Nowadays one of the main causes of death in the road are car accidents, these are caused due to known conditions like weather, state of the road, etc. The purpose of this Capstone Project is to build a data science model that help Us predict the possibility of getting into a car accident and the severity of it. This project is designed to help the local authorities take better decisions about car accident prevention and also for the public in general that could use this information as a tool to make better choices in their daily life.

## Data
To build this model We will use the shared data of traffic collisions from Seattle City. We will analyze the traffic collisions variables like weather condition, road condition, car speed and light conditions.
</br>Data will be extracted from: https://s3.us.cloud-object-storage.appdomain.cloud/cf-courses-data/CognitiveClass/DP0701EN/version-2/Data-Collisions.csv 
</br>The dataset has 194,673 rows with 37 different attributes.

## Conclussion
The purpose of this project was to build a data science model that would help us predict the possibility of getting into a car collision and the severity of it. This would help local authorities to take better decisions about car accident prevention and also for the public in general that could use this information as a tool to make better choices in their daily life. We did this first by understanding that a logistic regression model would be the best classification algorithm due to the variables found in the dataset. Then I had to identify the key independent variables: Weather conditions; Light conditions; Road conditions.

After cleaning and processing the data into the algorithm we can see that from one out of three collisions in the city of Seattle could end up in a serious injury for the persons involved. Whatsmore, using Jaccard's evaluation index we can also identify an accuracy of 67.27% for the prediction model. Finally, we can conclude that if we could have data of the cars not involved in a collision every time they go out to the road, we could take the prediction model to a new level. We could even try to predict if they would or would not get into a car accident. The possibility of having that kind of data would be wonderful, and thus with reason we can say that having good data is the new gold.
