Analysis of the Yelp Dataset
========================================================
author: Jerry Tsien
date: November 16, 2015

Introduction
========================================================

Based on the Yelp dataset from http://www.yelp.com/dataset_challenge, this analysis tries to find the relationship between the rating of a business (how many stars it has) and the number of reviews it receives on the website of Yelp (http://www.yelp.com/).

- The overall rating of a business is determined by majority voting (selecting the mode of all the individual ratings).
- The number of reviews are counted regardless of their content.
- For the purpose of this analysis, rating/stars and review count are calculated from the review file, rather than from the business file.

Methods and Data
========================================================

- The number of reviews for different ratings is plotted.  
- The percentage of businesses with higher ratings at different levels is calculated and plotted, in order to find the pattern.  
- When and where the pattern resembles a linear relationship, a regression model is established.  

![plot of chunk unnamed-chunk-1](Slides-figure/unnamed-chunk-1-1.png) 

Conclusions
========================================================

- More than 2/3 of all the businesses with reviews in the Yelp dataset are rated 4-star or 5-star.  
- The more reviews a business receives, the more likely it'll be rated 4-star or 5-star.  
- On average, 6 additional reviews for a business will increase the probability of its receiving 4 or 5 stars by 1%, when the number of reviews is less than 100.  
- When the number of reviews is above 50, more than 90% of these businesses are rated 4-star or 5-star.  
- It's impossible to separate 4-star businesses and 5-star ones solely by the number of reviews they receive.  

Resources
========================================================

- Original Data Source:  
http://www.yelp.com/dataset_challenge  

- Project Source Code:  
https://github.com/JerryTsien/Yelp  

- Final Report:  
https://github.com/JerryTsien/Yelp/Report.pdf  
or  
http://rpubs.com/JerryTsien/YelpReport  

- Slide Deck:  
https://JerryTsien.github.io/Yelp/Slides.html  
or  
http://rpubs.com/JerryTsien/YelpSlides  
  
Thank You!
