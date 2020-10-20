# Traffic Violation Causes & Accident Analysis

ABSTRACT

Data Set: Traffic Violations in Montgomery County of Maryland(Traffic_violations.csv).

This dataset contains traffic violation information from all electronic traffic violations issued in the County. Data sets on traffic violation presents an aggregated amount of data on all law eligible traffic stops in the state of Maryland. Basically, it consists of all traffic stops that occurred under Maryland jurisdiction for eight consecutive years/calendar years (2012-2020 latest month).

URL: https://catalog.data.gov/dataset/traffic-violations-56dda

Introduction: Violations in traffic laws are very common in a highly populated country like US. The accidents associated with these violations cause a huge loss to life and property. Being a metro city and a highly populated, has a lot of road accidents every year. Being a metro city and a highly populated state,Maryland has a lot of road accidents every year. Despite this the violations in traffic laws do not reduce. A lot of people disobey the rules every day sometimes willingly and sometimes because they are forced to do so because of others.

Traffic violations occur when drivers violate laws that regulate vehicle operation on streets and highways. More than 90% of Americans over age 16 are licensed to drive, often with more than one vehicle registered per name. That translates into trillions of miles driven each year and millions of traffic infractions -- including speeding, running red lights, reckless driving etc. Traffic violations are usually issued by local law enforcement officers and processed in local branches of state court.

Action Items: Predicting a comprehensive understanding of the reasons of accidents so as to determine the underlying cause of the same. Since it is a real time raw data we would start with our Data Exploratory process like handling the NaN values, Dropping few features which doesn't contribute in predicting our target variable and other Transformations. Our target variable is the "Accidents" coloumn.

We explore the relationship of the other features in the dataset with respect to Accident. We will the visualize the relation of all the other depend features with respect to our target variable,and hence find the most correlated features which effects our target variable.we would then implement the data in various Modelling structures such as Logistic Regression, KNN classifier, Random Forest. These modeling will then give us the accuracy of our prediction and then we could state which model gives us the most optamized and accurate readings.

Aim:
The goal is to increase the awareness among the people to follow safe driving practices and to decrease the number of traffic accidents/violations in future by including these statistics in traffic manuals.
