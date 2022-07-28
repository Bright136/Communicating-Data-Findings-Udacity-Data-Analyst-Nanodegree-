# (Communicating findings )
## by (Bright Ofori Boye Eshun)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area stored in 201902-fordgobike-tripdata.csv file. The idividuals have been group by gender(male, female and other) and by the type of users they are, whether subcribers or customers. They birth year of the individuals were also given, hence we can go to calculate for their ages since the year at the time was 2019. The data contains 183412 rows and 16 columns


## Summary of Findings

### Finding under the Univariate plots
>

> All the users rode for more than 250 secs, majority of them rode in the range 250 and 2000 secs. At around 250 secs, the number of trips began to increase from 8000 trips with an increasing in duration sec to 12000 then it peaks at 650 secs. We realise that the trips decreases from 1200 downwards as the duration approaches 2000 secs. From the age distrution we realize the distribution is skewed positively and also more trips are concerntrated between the ages of 20 and 40 with most of them being 31 years old. Amongst the users, subscribers occupied more than 0.75 fraction of the total and gender wise most of these users were males, occupying 74.6 percent of the total.


### Finding under the Bivariate plots
>

>All three genders had almost the same median duration but averagely, female and other took longer trips than males, which is interesting. Male, female and other had a lot of outliers when plotted(boxplot) against duration. Most frequest users who took longer trips were within the ages of 25 and 35 years. Also we realise that most users who crossed the 1000 sec duration were between the ages of 20 and 60 years. Most of the ages in all genders were also concerntrated around the ages of 20 to 40 years. Averagely, customers took longer trips than subscribers. There were more males subcribers and males customers than the other genders and this was not shocking because out of the total males were more than twice as much as females and more 30 times as much as others. 


### Finding under the Multivariate plots
>

>Interestingly, although when we plotted gender against duration, we found out other gender took longer rides than male and female, when the user type parameter was added, now we notice female customers took longer rides than the rest of the gender of customers but amongst subcribers the other gender took longer rides. We also notice that subscribers between the ages of 50 to 60 took longer trips than customers between the same ages. The distrinution of duration against age for both male and femal seems to have the same trend- as the age increases, the duration decreases, but for the other gender we can notice the same pattern except for the ages around 55 years where there is an increase in duration. The duration for old age in other is averagely higher. 

## Key Insights for Presentation

> In general users were within the ages of 18 to 104 and every user who took a ride passed the duration of 250 secs. In both subcribers and customers, although male was the majority, other and female took longer trips than male, which is very interesting. Some trips wereconsidered were considered outliers and this could a factor that contributed to this trend. Also customer took longer trip than subcribers except a portion of old age subsribers (50 - 60 years) who took relatively longer trips.

>Users between the ages of 25 to 35 took longer trips than the rest. This trend ran through both gender and user types. Most of the users were 31 years old and this could contribute to this trend.


>Majority of the users who took trips of 2000 secs were users below  45 years. We realised as the ages increases the trip duration decreases for all gender except in other where trip duration increased slightly for ages around 55 years. We realised a similar trend is users types between the ages of 50 and 60 who were subcribers compared to customers. They had relatively longer trip duration compared to customers. Could it be that this group of old age who are subcribers are of the gender other?