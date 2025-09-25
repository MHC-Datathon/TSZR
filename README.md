## MHC++ x MTA Datathon 2025
## Team Name - TSZR 
### Team Members - Tiffany, Sara, Zara 
#### [Click on here for Slide Deck](https://docs.google.com/presentation/d/1-3IXw0iE8VQ_0b0aUahq8Otvlld98QaLHnTVF3NJFz0/edit?usp=sharing) 
#### [Click here to view our Video Rundown](https://drive.google.com/file/d/1xkgmTeI3tB3tdb-TPzs-LzxR0N99fn2q/view?usp=sharing)

# Project Question 

### What factors impact the ACE violations at the largest hotspot? ###

# Contextualizing our Question 
<p> In this project, we kept these questions in mind:
  + How much do employees, students, and tourists impact the hotspot/ACE violations?
  + Is it commercial use? Car services? Related bus/train lines? 
  + Geographical? How are lanes structured? 
  + What demographic makes up these riders? 
  + What businesses are around these routes? Public/private schools? Universities?
</p>

<p> We also compared and contrasted two hotspots [Financial District vs Queens College route] to understand which factors are universal across NYC and which are unique to the dense Central Business District. Finally, we discuss our findings future steps. </p>

# Our Process
<p> We started by brain dumping all of our knowledge on the 3 provided questions. The three of us bring a unique perspective to our project, and it was crucial to note these differences to understand our connections and our relationship with the MTA. The two boroughs we found most interest in and familiarity with were Queens and Manhattan, which became the focal points of our project. Using MTA's open data portal, we consolidated various data reports to structure our main ideas. </p> <p> The data we used are:</p>

- [MTA Bus Automated Camera Enforcement Violations Beginning October](https://data.ny.gov/Transportation/MTA-Bus-Automated-Camera-Enforcement-Violations-Be/kh8p-hcbm/about_data#)
- [MTA Bus Hourly Ridership: 2020-2024 (362M rows)](https://data.ny.gov/Transportation/MTA-Bus-Hourly-Ridership-2020-2024/kv7t-n8in/about_data)
- [MTA Bus Hourly Ridership: Beginning 2025 (87.6M rows)](https://data.ny.gov/Transportation/MTA-Bus-Hourly-Ridership-Beginning-2025/gxb3-akrn/about_data)
- [MTA Congestion Relief Zone Vehicle Entries: Beginning 2025](https://data.ny.gov/Transportation/MTA-Congestion-Relief-Zone-Vehicle-Entries-Beginni/t6yz-b64h/about_data)

# Visualizing Data (Our Tableau Data Visualizations)

### Main data 
![hotspot](hotspots.jpg)
[MTA ACE VIOLATIONS](https://public.tableau.com/app/profile/tiffany.zhu8039/viz/MTAACEViolations/HotSpots)
![pre](pre.jpg)
[MTA PRE CONGESTION RIDERSHIP (MARCH 2024)](https://public.tableau.com/app/profile/sara.lukacevic/viz/March2024ManhattanBusRidershipPre-Congestion/Sheet1)
![post](post.jpg)
[MTA POST CONGESTION RIDERSHIP (MARCH 2025)](https://public.tableau.com/app/profile/sara.lukacevic/viz/MTAPost-CongestionRidershipMARCH20https://public.tableau.com/app/profile/sara.lukacevic/viz/MTAPost-CongestionRidershipMARCH2025/Sheet125/Sheet1)

<p> -- The source datasets for #2 and #3 were sorted hourly and by route, and so we aggregated the data for each day, regardless of the hour or route, for the months of March 2024 and March 2025 respectively. Then, we calculated the average throughout the month to compare Manhattan Bus Ridership before the implementation of congestion pricing (March 2024), and after (March 2025), given it was implemented on January 5th, 2025. </p>

# Analysis 
<p>
By analyzing the data, we noticed a particular, separate string of violation hotspots ourside Manhattan and decided to look into it more. After researching the context and surroundings of these violation hotspots, we found that it connects Queens College and other institutions to a very busy neighborhood. Many Queens College students, in addition to Townsend Harris High School and John Bowne High School students, widely use a select few bus routes. This is due to the fact that there aren’t any train stations or other modes of public transportation near the campus. These bus routes coincide directly with a string of high-violation hotspots, providing insight on the causes of these hotspots. These bus routes also directly cross Flushing-Main Street, an area that is also very busy, being a central hub for many people, buses, cars, and acting as an economic center for many businesses. 

Therefore, after conducting more research of the context and surroundings of violation hotspots, we found that many landmarks, tourist attractions, transfer locations, and college and institutions are in the vicinity of many violation hotspots, and that these factors aren't only unique to Manhattan.
</p>

![queens](queens.jpg)
[queens](https://public.tableau.com/app/profile/tiffany.zhu8039/viz/MTAACEViolations/HotSpots)
![financial district](financialdistrict.jpg)
![landmark](landmark.jpg)
[landmark](https://www.6sqft.com/new-interactive-map-lets-you-explore-new-york-citys-landmarks/)
![cuny](cuny.jpg)

# Summarizing Final Findings + Insights 

<p>Ridership for Manhattan buses has increased by nearly 20,000 riders per day on average, with this number being even higher on business days, when comparing the months of March 2024 and March 2025, before and after congestion pricing was implemented. As there is increased ridership after congestion pricing was implemented, it may suggest that more people are opting for public transport to avoid the tolls, if this trend of increased ridership between 2024 and 2025 continues.
<br> <br>
We also found that 45% of the ACE violations issued are located in Manhattan and Queens during 2024-2025. In addition, violations issued in Manhattan have increased by 26% while decreasing 18% in Queens. This increase in Manhattan violations is also related to the fact that more Manhattan buses have been added to the ACE program in the recent months. This provides context to the statistic, displaying that an increase in violations may be due to the addition of new ACE routes where drivers and businesses are still acclimating.
<br>
Many of these violation hotspots also coincide with major landmarks, tourist attractions, and colleges and institutions, displaying a correlation between high-traffic and attraction areas and violation hotspots.
<br>
</p>


# Final Message + Possible Next Steps

<p> As next steps, we would analyze bus speeds to better understand how the ACE system affects transit efficiency. We also plan to expand our study to include MTA train ridership, evaluating the broader impact of congestion pricing on Manhattan’s public transportation. Additionally, we could identify which bus routes should be added to the ACE program as a priority, helping to optimize enforcement and improve overall transit flow. </p>


