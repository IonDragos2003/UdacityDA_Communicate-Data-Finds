# UdacityDA_Communicate-Data-Finds
(https://www.mercurynews.com/wp-content/uploads/2018/01/salm0728bikes022.jpg)
# Dataset

Bay Wheels (ex FordGoBike) is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.
Historic datasets can be found here

## Data wrangling process:
* Change the column type for date columns: start_time, end_time should be datetime type 
* Change the column type for: user_type and bike_share_for_all_trip - should be categorical data type
* Add new columns for trip duration in minute, trip start date per month and per day of the week
* Calculate total distance traveled

## Findings

Firstly, there are two types of customers for this program: subscribers (as the more frequent users) and customers (as less frequent users). 

* The peak of rides are during sommer months up until late fall, which is expected (most likely correlated with temp).
* More rides during weekdays than weekends, indicating most likely that the scheme is used for commutting.
* The average duration of a trip, irrespective of type of customers is around 9 minutes.
* The average distance traveled (in km) is around 1.6km, where 75% of the users travel at least 2km on average.
* Based on the total number of consumers of the scheme in 2018, 85% of the users are subscribers, which is much more than what I personally expecting, indicating the scheme appeal to commuters.
* When looking at customers vs subscribers usage per month, they are pretty much correlated, indicating again a linkage with temp
* However, when looking at usage per day of the week, subscribers use the scheme more during weekdays (most likely for commuting), whereas customers use the scheme more during the weekends (for leisure).

More findings inside the jupyter notebook.

## Project files:

* README
* Analysis notebook (+ html version)
* Slide Deck notebook (+ html version)
