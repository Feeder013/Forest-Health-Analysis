# Forest-Health-Analysis
This repository contains the complete analysis of forest data across the whole USA using Jupyter notebooks and Tableau

1.0	FOREST HEALTH STATUS ANALYSIS

1.1	DATA BACKGROUND

The data contains information about forest trees located at different places in the US obtained from Kaggle. The data contains 1000 rows of information such as Temperature, Humidity, Diameter at base height, Gleason index, disturbance level, etc. The only categorical data is the health status of trees. The research questions proposed to be analyzed in this project include: (a) What is the abundance of species as well as ecological diversity on the different tree statuses (b) Is diameter at base height in correlation with Elevation (c) What is the distribution of trees by status at different locations. This project was treated using Python Programming Language and some visualizations were made using Tableau.

1.2	DATA CLEANING AND PREPARATION	

The following steps were taken in cleaning and preparing the data for analysis: 
•	The data contained no duplicates or null values that need population. There were no blank rows or invalid data either

1.3	EXPLORATORY DATA ANALYSIS
	
 These were the steps employed in exploring the data, deriving information using different samples of it to gain insights and construct models:

•	A barplot was made showing the frequency of the different categories of health status
•	The DBH against Disturbance Level by Health status with tree height as size model was made using the Seaborn library
•	The Gleason index by fire index grouped by health status with tree height as size scatter plot was modeled
•	A correlation model for elevation, weather conditions, and disturbance level of species
•	A regression plot for the fire risk index against temperature

1.4	DATA INTERPRETATION 

The following inferences, observations, and insights were obtained from the complete analysis of the forest health dataset:

•	A filled map displaying the distribution of healthy and unhealthy trees across the US shows that the health status is widely and evenly distributed in the regions and as health indicator comes into play infection rate might increase in healthy ones too with high proximity. 
•	Tall trees with an average height of 22m at an elevation above 1,400m tend to be very healthy trees protecting and affecting the balance of biotic and abiotic components.
•	Unhealthy trees have a higher disturbance level > 0.8 irrespective of the tree at breast height diameter
•	Unhealthy trees have a low Gleason index (low richness of ecological species which is an accurate representation of the ecosystem). 
•	Increasing ecological diversity and abundance can improve tree health 
