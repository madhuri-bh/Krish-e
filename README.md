Farming solution : By agventures
    Idea
Krish-e –android application
We have focused our attention on -
Module1: that would allow farmers to treat their plant diseases. We 
are using Tensorflow library(Machine Learning library) to detect plant 
disease. The farmers can use their smartphone to scan a particular 
plant leaf which they suspect for having a plant disease. We analyse the 
plant diseases, symptoms etc and then generate proper measures to 
improve plant health.
             Module 2 :
1.Data Collation
   (1). At first the Air humidity, Air temperature, Soil moisture, Soil pH and the GPS sensor modules are 
integrated with the NodeMCU platform into a portable kit. This kit is installed in the farm to 
gather the respective data of the soil. The data gathered is transferred in real time to firebase 
database for storage and further processing.
    (2). The atmospheric humidity, temperature, soil moisture, soil pH are sent as it is to the database. 
The latitude and longitude sent by the GPS module is retrieved in the form of which state they fall 
under. This enables us to collect the rainfall of that place in the previous year.
2.Data Processing Using Machine Learning :
    (1). Crop Prediction:
    (2). Price Prediction:
3.Implementation using Android Application After the predicted data gets reflected in the 
firebase database, the farmers can view it in their mobile application.
4.They can know what crop to cultivate and what at price at which the crops should be sold 
to earn reasonable profit for the farmers
