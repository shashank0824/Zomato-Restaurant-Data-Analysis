# About Dataset
Zomato EDA is one of the most useful analysis for foodies who want to taste the best food of every part of India which lies in their budget also and for those who want to find out the best rated, most voted, value for money and features like online delivery restaurants in their cities. With this data set analysis foodies will get many answers for their queries. 

# Dataset details
Zomato dataset cointains following columns:
1. Restaurant ID : Unique id of every restaurant across various cities of India.
2. Restaurant Name : Name of the restaurant.
3. Country : Country in which restaurant is i.e. India.
4. City : City of the restaurant.
5. Address : Address of the restaurant.
6. Locality : Location of the restaurant.
7. Locality Verbose : Detail of the locality of the restaurant.
8. Longitude : Longitude coordinate of the restaurant’s location.
9. Latitude: Latitude coordinate of the restaurant’s location.
10. Cuisines: Cuisines offered by the restaurant.
11. Average Cost for two: Cost for two people in the restaurant.
12. Currency: Currency of the country.
13. Has Table booking: yes/no.
14. Has Online delivery: yes/ no.
15. Is delivering: yes/ no.
16. Switch to order menu: yes/no.
17. Price range: range of price of food.
18. Aggregate Rating: Average rating out of 5.
19. Rating color: depending upon the average rating color.
20. Rating text: text on the basis of rating of rating.
21. Votes: Number of ratings casted by people.


# Tasks to Compelete are :
1. City with cheap restaurants
2. City with largest number of votes
3. City with most expensive restaurants
4. City with excellent rating
5. From which city maximum hotels are listed in Zomato and from which Locality
6. How many of restaurants accept online delivery

# Steps for EDA
Importing Dataset : import the data set using python library Pandas.

have a look at the dataset using .head() meathod.

Drop some not useful columns like currency.

Check for null values in the dataset using .isnull() method. If any null value is found fill it with either mean or mode.

After the data clean up, now look at the tasks to complete. 

To understand the rating count, group the data by rating columns and create a new column named as "rating count". 

plotted countplot for understanding  "no. of restaurant supports online delivery" and barplot for "maximum no. of restaurant listed on zomato", "City with top rated restaurant", Top 10 cuisines on zomato", "Top 10 city voted on zomato", "Cities with cheap restaurant" and "Cities with most expensive restaurants".

Users can find out many other things using this Zomato EDA 

# Conclusions
From this EDA we've drawn many inferences like: 
1. Restaurants rating is categorized in six categories - "Not rated, Average, Good, Very good and Excellent".
2. Most of the restaurants in India does not support online delivery.
3. Delhi has the maximum no. of restaurant in India and in Delhi, Connaught Palace have the maximum restaurants listed on Zomato.
4. New Delhi has the top rated restaurants of India.
5. "North Indian" is the top cuisine on Zomato followed by Chinese and Fast food.
6. "Bangalore" was the  top Voted city on zomato.
7. New delhi has the cheapest restaurants of India and also the most expensive ones.

# References

Dataset : https://www.kaggle.com/shrutimehta/zomato-restaurants-data 
(This dataset is for whole world)
