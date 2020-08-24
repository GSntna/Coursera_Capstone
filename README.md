# Coursera_Capstone

## Introduction

### Description and Background
Guadalajara is a metropolis in Western Mexico and the capital of the state of Jalisco. The metropolitan area of Guadalajara is the second largest of the country and is an international center of business, finance, arts and culture as well as the economic center of the Bajío region, one of the most productive and developed regions in Latin America.

For this project, we will take the metropolitan area of Guadalajara, which includes Zapopan, Guadalajara, Tlajomulco, Tlaquepaque and Tonala as boroughs/counties and try to find the best neighborhood to open a Gymnastics Business based on the USA Gymnastics recommendations for opening on of these type of facilities.
To do this, we will cluster the neighborhoods based on their nearby venues (using Foursquare API) after segmenting them by their spending capacity (based on the Housing Sales Prices), so this project may also result useful to anyone looking to open a business in the metropolitan area of Guadalajara.

### Data Description
For the project we used the following data:
  * An Excel file provided by the Geographical and Statistical Information Institute of Jalisco (IIEG) that contained a list of 17,700 prices of houses on the different neighborhoods in the metropolitan area. This database was built on April 2020, so we used the change rate from the end of that month (24.207 MXN/USD). 
  * Foursquare API to get the most common venues for each of the selected neighborhoods.
  * The geopy.geocoders library to get the coordinates for each neighborhood.
