# CitiBike Analysis Using Tableau

Using citibike data included in this repo, an analysis was performed of citbike use in June of 2013. 

This analysis intended to answer questions about users of citbike including age, durations of trips, gender and hours of the day when rides begin.

The completed analysis is available on Tableau Public. It can be found here:
https://public.tableau.com/app/profile/erick.adame/viz/ErickAdameCitibikeAnalysis/StartTimebyGender?publish=yes

# Analysis

Below is a sample visualization that examined avg trip length of citibike users by age. Interestingly enough, there's a spike in duration of trips for those around the age of 28 years. Outside of that outlier, regardless of age, that average duration usually falls between 15 and 25 minutes. There's a notable drop in duration for the oldest riders. The data included what is likely bad data with ages over 100 years. This was filtered out until it can be determined if that data is valid.

 <img src="/images/age_duation.png?raw=true">

This analysis also examined ridership patterns by gender. There was a very large number of indentification as UNKNOWN for gender. This data was included simply for trasnaprency that the gender could be either non-binary or simply left blank or perhaps any other reason. Of the data that was available, males seemed more likely to take trips late in the day that could carry into times when the sun is down. 

![Alt text](relative%20path/images/gender_patterns?raw=true "gender patterns")

An overall summary was completed also to determined popular start and end locations across the citibike network. Not surprisingly, many very popular end points are near Central Park. This data could be compared to winter data to determine if commuting patterns differ more dramatically when compared to leisure rides and rides completed by tourists.

![Alt text](relative%20path/images/station_patterns?raw=true "gender patterns")
