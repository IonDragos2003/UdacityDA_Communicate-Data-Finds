# UdacityDA_Communicate-Data-Finds

# Dataset

Bay Wheels (ex FordGoBike) is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.
Historic datasets can be found here

## Data wrangling process:
* Change the column type for date columns: start_time, end_time should be datetime type 
* Change the column type for: user_type and bike_share_for_all_trip - should be categorical data type

* add new columns for trip duration in minute, trip start date in yyyy-mm-dd format, trip start hour of the day, day of week and month
