# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project is to use Foursquare API and Yelp API to retrieve information so as to construct a dataset. The dataset will ultimately be used to construct a statistical model. This project also develop skills in using APIs, performing exploratory analysis, data cleaning and data visualization.

## Process
### 1. Choose a city so as to retrieve all the bike stations of a certain company, which are found within a 1000m radius from the city in question. I have chosen Vancouver as my city and mobibike as the bike company.
### 2. The next step is to use the both Foursquare API and Yelp API to get all pastry shops and flower shops that are found within a 1000m radius of the bike stations.
### 3. Performing a comparative analysis to see which API brings better result.
### 4. Merge the different datasets on common grounds so as to perform further analysis and data visualizations.
### 5. Build a regression model and discuss results.

## Results
Both Foursquare and Yelp API produce the same amount of data in terms of rows. The Yelp API offers a comprehensive dataset with split columns, providing more granular information. Also Yelp API has ratings for restaurants which is a very important factor while Foursquare API miss this important detail. The rating is helpful for more in depth analysis.




## Challenges 
My main challenge was to implement a loop to iterate through each bike station's coordinate. It worked for Foursquare API but I could not implement the same process for Yelp as I was having too many error messages. Finally, I had to continue my work without the loop.

## Future Goals
I would like to explore other cities and conduct a much deeper analysis in terms of data exploration, data visualization model building. 