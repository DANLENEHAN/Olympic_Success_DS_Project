# Olympic_Success_DS_Project
This repository holds all the notebooks and data created and used in the creation of my final third year Data Science project on Predictive Indicators of Olympic Success. The project was completed in a group of two my partner in the project : https://github.com/Danmaguire


Why Winners Win
Predictive Indicators of Olympic Success

Introduction
--------------
Project Looks at the effect that multiple factors have on a Countries ability to succeed in the
Olympic Games. The focus will be on Games between 1960 and 2016 and the facotrs that will be examined
are as follows:
	- GDP
	- Population
	- Politics
	- Home Advantage

Authors:
Daniel Maguire - daniel.maguire@ucdconnect.ie
Daniel Lenehan - daniel.lenehan@ucdconnect.ie


Notebooks
------------
To order in which all notebooks should be run is specified by the number at the start of the notebook title, 
i.e. notebook 100-example.ipynb should be run before 150-example.ipynb.

---Prep---
100-Obtain_Country_Data.ipynb
 -Downloads the .csv files for all of the countries from the world bank

200-Country_Preparation.ipynb
 -Creates the initial data frame for the countries using world bank data

250-Removing_All_Countries_Without_Medals.ipynb 
 -Removes all countries who have not won medals in the games either on thier own or while part of a larger team

275-GDP_Null_Values.ipynb
 -Deals with filling in null values present in GDP column

300-Geographical_Nulls.ipynb
 -Deals with null values present in area, longitude and latitude columns of dataframe

325-Get_Elevation_Range.ipynb
 -Deals with null elevation data and finds the elevation range of every country 

350-Education_Index.ipynb
 -Inserts data on the education index of each country from 1980 onwards

400-Other_Olympic_Teams.ipynb
 -Deals with teams that no longer oexist or for which we did not have required data

500-Olympic_Medals_DF.ipynb
 - This Notebook is for creating the dataframe that contains all the rows associated with the winter and summer games medal winners.

550-Medals_and_Ath_Age.ipynb
 - This is the notebook for getting the information on the ages of each individual athlete by scraping the Olympic website.

600-Olympic_Athlete_Numbers.ipynb
 - This is the notebook for getting the information on the number of athletes as well as the gender split for every country at every games.

700-Olympic_Medals_and_Athlete_Numbers_DF.ipynb
 - Joining the Medal df from notebook 500-Olympic_Medals_DF with the Athlete number df from 600-Olympic_Athlete_Numbers to have a df with the Medal winner information as well as the athlete information.  

800-Olympic_NOC_Rankings.ipynb
 - This notebook calculates the ratings for each country for every olympics and then each countries ranking for every olympics. 

900-Olympic_Athlete_Rankings.ipynb
 - Creating two ranking fields for all the athletes in every olympic games one for a given athletes rank in a given games and another ranking field for overall rank in the olympic games. 

950-Final_Medal_DataFrame.ipynb
 - Creates the final medal dataset containing all the fields related to the Olympics for the medal winning countries 

1000-Joining.ipynb
 -Joins the country and medal data frames together and creates data for analysis

1100-Execute_Prep.ipynb
 -Runs all notebooks excluding the 550 and 100 `


--Analysis--
100-Network_Analysis-Podiums.ipynb
 - Creates networks showcasing the relationships between countires that meet on the podium of an event in each of the games.

150-Network_Analysis-Competitiveness.ipynb
 - Creates networks showcasing the competitiveness between countries that meet on the podium of an event in each of the games.

200-Population.ipynb
 - Does basic analysis population work

250-Population-CSV.ipynb
- Creates the population csv used in the population analysis for RQ2

275_Pop_Prep.ipynb
- Creates all the nomralised fields needed for RQ2/ Population analysis 

300_RQ3_GDP.ipynb
 - The complete analysis of GDP

400_RQ2_Pop
 - The complete analysis of Population/ RQ2

500-Education.ipynb
 -Does the basic analysis for Education as a factor 

600-Elevation.ipynb
 -Does the basic analysis for elevation as a factor 

700-Execute_Analysis.ipynb
 -Executes all above analysis notebooks



--Final--

50-Run_Analysis+Prep.pynb
 -Executes all previous notebooks

100-Winners.ipynb
 -Looks at who are the most winning teams in the Olympics using different metrics

200-Home_Advantage.ipynb
 -Our final notebook which deals with the Home Advantage research questions

500-Education.ipynb
 -Notebook deals with results for education (This notebook was not used for our results)

600 - Politics.ipynb
 -Looks at the effect of political influence on Olympic success



