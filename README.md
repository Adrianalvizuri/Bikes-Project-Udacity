# 2020 Bay Wheels # Ford Gobike Data Exploration
## by Adrian Alviuri

## Dataset

Bay Wheels (previously known as Ford GoBike) is a regional public bike sharing system in the San Francisco Bay Area, California. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States with nearly 500,000 rides since the launch in 2017 and had about 10,000 annual subscribers as of January 2018. The dataset used for this exploratory analysis consists of [monthly individual trip data](https://www.lyft.com/bikes/bay-wheels/system-data) from January 2018 to December 2018 in CSV format covering the greater San Francisco Bay area

##### Data wrangling process:
- Incorrect data types.
- Create new columns using start time and duration sec columns.
- Create age column.
- Check for outliers and delete them.
- 'member_birth_year' and 'member_age' to integer data type.
- Dropping outliers


## Summary of Findings

Bikes are most used at 8am and 5pm. This can tell us that bikes are being used when people go to work and leave. When we see the trip distribution over day of week plot, the vast majority of rides takes play between monday to friday (work days). Compared to other months, october has the most trip, but people tend to use bikes in summer. That's why we can see more use between May and September.

There were more male riders than female and most members were subscribers. Also, members did not use bike share for all of their trips and the age of the vast majority of members is between 25 and 45. Most of the rides didn't last much. Nevertheless, we can see some outliers like 24hrs.

The usage for subscribers corresponds to their high concentration on rush hours Monday through Friday which indicates that the use is for work commute in the vast majority of cases. The interactions between features behaved as expected, there's no big surprise observed. There were more male data collected, but the only thing that could be is that males take shorter rides than women.

