---
title: "Assignment 3"
categories:
  - Blog
tags:
  - assignment
toc: true
toc_label: "Content Directory"
toc_sticky: true
---

# Spatial Data

## **Introduction**
For this assignment on Spatial Data, we have chosen to explore the source of **[The Brooklyn City and Business Directory 1879-80](https://archive.org/details/1880BPL/page/n21/mode/2up)**. This historical data set is a directory to businesses, government agencies, public services, and residencies in Brooklyn, New York, USA in the years 1879-1880. The source includes, in this order:

**-The name of the business or business owner**

**-The occupation**

**-The address of the business**


This provides us with a unique shot of Brooklyn in the late 19th century, where we could observe the urban development of late 19th century Brooklyn to the early 21st century Brooklyn that we will see through visualizing our data using Kepler.gl and eventually, through our own eyes once we fly to the New York campuses of New York University when we are on our study aways.

We chose this source out of the eight other sources because of our **different interests** in the United States. Given that we’re both American, we wanted to explore data from the American past more. 

Linus’s background is from *California*, so it would be interesting for him to look into content from New York, specifically *Brooklyn, New York*. Elizabeth is originally from *Manhattan, New York,* so she also wanted to explore content in another area of New York that she is **not familiar with**. 



## **Data Collection**

Our data collection process began with the selection of 2 random pages, **221-222**, where we then copied the words of the entire page, and created a csv file of the data using chatgpt.Attached below is the page we have selected. 

![Directory](/assets/images/Directory.png)

 We were able to manually copy and paste from the page onto chatGPT because there was an OCR layer already applied on to the source. The prompt we provided chatGPT with was: **“Make a CSV file with and only using the above data with 50 rows.”** 

 We attempted to tell chatGPT to create more rows of data, but when we tried that, chatGPT began to make up data or repeat data. The keyword **‘only’** was also crucial in the prompt that no new data was being created.

With the CSV file created, we uploaded it to Google Sheets. The columns include the name of the business owner, their occupation, the location of their business. Using **Geocode by Awesome Table**, we were able to produce longitude and latitude data from the given addresses. 

As all the addresses were located in Brooklyn, we added **"Brooklyn"** in front of all the addresses in order to improve accuracy. This actually massively **improved** the amount of addresses recognized, as the first time we ran the geocode without the addition of Brooklyn, **only 10 addresses** were recognized. The Geocode was able to provide 35 out of 50 longitudinal and latitudinal data. 

We are unsure whether the remaining 15 were a result of Geocode not being able to produce the data or an error with the data from the OCR. 

![Brookyln](/assets/images/Brooklyn.png)


## Data Visualization


Using **[kepler.gl](https://kepler.gl)**, a powerful web- based app that helps with visualizing geolocation data, we were able to provide a **visualized map** from the CSV.

Due to the nature of the data, there were **no repeats and meaningful grouping** of the data. Most of the occupations were different and grouping by name doesn’t really provide much insight. It *did* however, provide spatial information of the business distributions in Brooklyn during this time.

![Brooklynkepler](/assets/images/brooklynkepler.png)

A few of the data points created when placed on the map led me to discover several points that were far from Brooklyn. Upon further investigation on these points, we discovered that these mistakes were due to the names of the addresses **having the same names** as major cities within other states and areas. 

For example, the dot on California had the name **‘Oakland’** in its name and the one in Georgia had **‘Macon’**, *both* major cities of these respective states. 

Therefore, these mistaken points were caused by the geocoding process, incorrectly interpreting the addresses. 

![USAkepler](/assets/images/USAkepler.png)

## Possible Applications

A part of this assignment journey that we found the most intriguing was **tracing the historical evolution** of the city. 

As the Geocode generated specific locational data via longitude and latitude, we were able to search up the location described in one of the columns on google maps. We searched up what was **originally** the location of a *carpenter* in the 1880s, and found out it is **now** a *Child Development support corporation*. 

![Carpenternow](/assets/images/carpenternow.png)


Noticing a change like this, where a manufacturing site turned into a social service facility, shows the *dynamic changes* that must have taken place throughout this part of Brooklyn, and how the neighborhood’s resources will change and evolve accordingly to the **needs of the given community**. 

This usage of geocode and mapping the locations from the past is an interesting way of *documenting the evolution* of particular locations in not just Brooklyn, but **other** cities and countries as well. 



## Conclusion

Overall, this project not only enhanced our understanding and experience with spatial data visualization, but also *introduced us* to **another idea** of visualizing datasets, particularly on a map, while also understanding the urban development of a city we are both not familiar with. 

In our previous assignment, we were able to better visualize our data using **word clouds**, but with this assignment, we visualized the data *even more*, creating maps where we were able to see the **clear area** of where such businesses stood. 

With a larger data set, we may be able even more clearly identigy hotspots for businesses and perhaps even hotspots for specific businesses. This was **not** possible on the size of data we analyzed due to the lack of repeating businesses. 

In addition, due to our selection of one page only, and the document being printed in alphabetical order, there were **not** many conclusions we could draw based on the names of the business owners. 

This project also exposed many of the limitations of both OCR in correctly identifying text and also with Geocoding with correctly providing locational data. 

Throughout the process of completing this assignment, we realized that we should’ve, and wanted to explore the realms of New York University in Brooklyn more. As we are both students of New York University (Abu Dhabi) and the data was in the 1880s, we were curious to see if we could have found any information on New York University New York because it was founded in **1831**. 

Given *our NYU status* and the fact that we will both be going on a study away in New York, specifically Brooklyn, New York, for to attend NYU Tandon, we *wish* we could have explored the residential and business directory listings to see if anything from NYU could be found for our assignment, *assuming* that it started flourishing a lot more by 1880. 

NYU Tandon in specific was founded in **1854**, so its data would have still worked if we had thought about it sooner before we did the majority of our assignment. We think that would have been a very interesting approach to this assignment, where we get to learn more about spatial data and visualizing that data, all while **learning more** about our sister school from way back in the 1880s.

For **future** assignments relating to spatial data visualization, we hope to expand the dataset to include more than just a few years in one borough. 

It could end up being a lot more interesting if we expanded to a decade in all of New York City, as each borough has its **own characteristics** in *population, population density, diversity, types of community, etc.* 

We would also want to incorporate the data that we will be learning from with data that we might already know or are familiar with, to add *another* **interesting layer** to our data and research. In this case, it would have been cool to work with NYU Tandon, but maybe in the future, we could expand to Manhattan as well, and then compare all of NYU New York’s undergraduate and graduate schools to compare and contrast. 

We could also expand the years so we could see what was built ***(if anything at all)*** before the NYU buildings and see how it compares to now. We could even just see how much the buildings themselves might have developed over the years from any reason ranging from development to destruction due to natural causes.



