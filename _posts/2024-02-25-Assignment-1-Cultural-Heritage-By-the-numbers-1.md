---
title: "Assignment 1"
date: 2024-02-22T15:34:30-04:00
categories:
  - blog
tags:
  - assignment
---
# Cultural Heritage By the Numbers
## **Part 1**

*HAM Website:*
The website is easy to navigate, and has a simple user interface. By using generous interfaces, users get to scroll and explore through the collections without having to have a particular piece in mind to search for. The visuals help play a part in intriguing users and capturing their attention without actively trying to search for something. Users are also able to filter pieces by classification, work type, medium, technique, period, place, century, culture, and/or gallery. There are also many subcategories within each filter, making it a lot easier for people to search for a specific type of work. We found it to be relatively accessible because the pictures and fonts were a decent size and in a font/color that is easy to read. In addition, the website is able to provide visuals, title, object number and classification without having to click into the object, making it convenient for users to explore around many different mediums of work  

The piece that caught our attention was: [Chicken Noodle Soup](https://harvardartmuseums.org/collections/object/262968?position=262968). Through the website, we were able to access related personnels that took part in the creation of the piece. Other information that was available to us through the website were the date of creation, type of art, cultures related to the piece, dimensions, and even physical descriptions of the medium. Two details we found to be interesting were accession year and location. The accession year tells you the year the museum acquired the piece, and the location tells you where the piece is located within the Harvard Art Museum, and users are even able to view the piece’s location on their interactive map. 
*CSV:*
The organization of pieces within the CSV files seems more structured when compared to the website, however, we couldn’t distinguish the exact method of grouping that was utilized when creating the csv. The CSV is able to provide more information on each piece of art without the need of accessing specific pieces. The CSV allows you to analyze the metadata much more efficiently through scripts such as the API provided in the positcloud. 

Conclusion:
The website is more user friendly and visually appealing. However, the website is more geared towards the obtainment of data for individual pieces, whereas the CSV allows for a broader analysis of the collection of pieces possessed by the museum. 

#**Part 2**

After looking at the 254 rows of All_culture_information.csv, we noticed that the culture with by far the most items in the collection is American, coming in at 90,115 objects. This is followed by a big decrease to German at 35,600 items and French at 26,040 items. Following is Italian, at another big jump downwards at 12,501 items and British at a close 11,114. From this, it is very clear that a contemporary US museum shares a lot of works from the Western American world, as well as other Western European countries. We noticed that the culture following British is Japanese, which is not a Western country. However, Japanese, along with all of the cultures mentioned above, were all at some point, colonizer countries. This led us to think about how many of the pieces here might’ve been of other original origin, but were transported or donated to the colonizing countries out of difference in power dynamics and wealth. While there are plenty more cultures within the cultures, the pieces that those cultures possess are far less than the aforementioned cultures. The collection is still majority composed of pieces from western cultures. For our culture, we chose Korean, and the piece that was most viewed (1.1k views) according to the Harvard_API_ALL_objects is a vessel with the title [“Large, Broad-Shouldered Jar with Decoration of Two Striding Dragons, Each Pursuing a Flaming Jewel”](https://harvardartmuseums.org/collections/object/70504). ![Vessel](/assets/images/vessel.jpeg) The piece that was the least viewed (0 views) was a fragment titled [“Sherd: Portion of the Lip of a Vessel, Probably a Jar or Bottle”](https://harvardartmuseums.org/collections/object/76983). ![Fragment](/assets/images/fragment.jpeg) The most viewed object is a beautiful jar decorated with a drawing of two dragons, although being a Korean piece, the piece is something that is able to be enjoyed by people from all cultures and backgrounds. The art is very visually pleasing, and there are a lot of small careful details especially done in the scales and face of the dragon, which can draw attention from people who were browsing through collections. We searched the title of the piece on Google, and another Jar of very similar design and the same description was described as a “rare and important blue and white porcelain dragon jar for the Korean Royal Court,” and it was bid on for $3,890,500, which shows how valuable it is, which could be linked to why it has so many views. Obviously, not everyone can afford bidding for an expensive and valuable vase from the mid-18th century Joseon dynasty, so they may want to look at the piece in other ways. Some of the viewers might’ve been people who found it beautiful when they saw it in the collections, others might have wanted to learn more about pieces from the Joseon dynasty at this time, and some others might have known about the piece and wanted to use the website to find the location of the piece. There are many other possibilities as to why people would view this piece, but those are a few inferences we made. On the other hand, the least viewed piece is a fragment, with its origins being unknown as well. The reason why this could be the least view may be because of how unflattering it looks. There is nothing really nothing to grab on to a person’s attention, it is just a broken piece of something. Without any context, you couldn’t really identify what you are looking at. The uncertainty in the title may also play a part as it adds a very informal feel to the piece. Even the museum doesn’t have enough information on what it is, which makes it seem very irrelevant. If people were browsing through the collections visually, without clicking onto specific items, this piece would likely be overlooked in comparison to other pieces that are not broken fragments of “probably jar" or in comparison to other pieces that are a lot more visually appealing and would be considered more like art rather than scrap. In comparison to the dragon jar, this piece holds no cultural significance or value, which can also make it not a very compelling piece of work. Alongside lacking cultural significance and value, it also lacks purpose and functionality. It doesn’t tell a narrative either, making it seem like something with no significance of any sort.

# **Part 3**

The three cultures we chose were Korean, Chinese, and Japanese, the three most popular East Asian cultures. 
![Korean](/assets/images/originalkwordcloud.png)
![Chinese](/assets/images/originalcwordcloud.png)
![Japanese](/assets/images/originaljwordcloud.png)
The original word clouds contains a lot of articles which obstruct from the true frequency of words that actually describe the pieces. After using the stopword function, here are the following wordclouds: 
![Korean](/assets/images/Finalkwordcloud.png)
![Chinese](/assets/images/finalcwordcloud.png)
![Japanese](/assets/images/finaljwordcloud.png)

A recurring theme within the Korean word cloud are words related to architecture, pottery and ceramics. Some of the words that describe it are: decoration, decor, fragment, wall, bowl, sherd, vessel, etc. 
As for the Chinese word cloud, there are a lot of keywords that have to do with nature, such as bamboo, flower, mountain, and leaf
In the Japanese word cloud, the most prominent words are tale, poem, and series along with some famous landmarks in Japan. I believe this shows the acquisition of mostly literary pieces from Japan 
From each of the word clouds, we can infer that a reason why these East Asian cultures are important to an American museum is because of pottery and ceramics. Given the origin of pottery/ceramics from East and Southeast Asia, it makes sense why keywords that tie back to pottery and ceramics show up so frequently. 

As for the results after the stopwords, it is relatively the same. Each culture’s word cloud stuck to the same general theme, only without articles such as the, a, an, etc. With this, there seems to be greater emphasis on culture, since these articles are removed. The removal of these terms allows for more culture, art forms, and history to be displayed. 


![barchart](/assets/images/barchart.png)
Through the barchart, we are able to see the trends of the years where the museum obtained the most pieces from each culture. In the 1930s to 40s, it was nearing the end of World war II and the 50s was when the war was officially over. This period saw an increasing influx of Japanese and Chinese pieces into the museum. This correlation could be a possible explanation for the abundance of pieces from China and Japan during this time period. In the 1980s, Japan is rebuilding their economy and making an effort to put their self back on the global scene following the war. This could explain the increasing accession of pieces into the museum, due to an increasing interest in Japanese culture and art. 




Citations:
https://www.christies.com/en/lot/lot-5416450 

Ready for grading

	

