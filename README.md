# Satellite Analysis

Link to Tableau Public: https://public.tableau.com/shared/BM4NZ96YS?:display_count=n&:origin=viz_share_link

## Overview
In this project, I strive to visualize some interesting data about satellites orbiting the Earth. In order to achieve this I merged two datasets: 
UCS Satellite Database: https://www.ucsusa.org/resources/satellite-database
Number of satellites launched from 1957 to 2019 (Statista): https://www.statista.com/statistics/896699/number-of-satellites-launched-by-year/#:~:text=In%202019%2C%20there%20were%20a,114%20satellites%20launched%20in%202018.

The first dataset provides detailed information about the currently-active satellites, such as name, owner and contractor country, users, purpose, class of orbit, launch date, etc. The second dataset simply provides the number of satellites launched for the period of 1957 to 2019, helping to benchmark the currently-active number of satellites with a more global and historical picture.

## Approach and Results
I love space, so I quickly focused my search into data about space. After testing couple of ideas, I found the UCS Satellite Database and officially chose this topic. However, after cleaning the data it became apperant that I would need additional data, since the currently-active satellites are just a small percentage of all the satellites ever launched. The data I found on Statista helped me fix this issue and after a brief cleaning I started to visualize the data. The first graphs I created were the total number of active satellites per year, total launches per year, and compareson between those two (as shown in the story). I noticed that there was a huge increase and drilled down to find out why. After conducting my research I found that SpaceX, a new commercialized player was delploying thousands of small satellites in lower orbit as a part of their Starlink project (which promises to bring Internet everywhere on Earth). I visualized my findings on slide #4 of the story board. Moreover, I decided to visualize a timeline of the world, showing the development of countries who own a satellite. Additionally, I filtered and sorted the top 5 launching vehicles and launching sites. Finally, I decided to visualize the distribution of satellites based on their class of orbit, users and purpose, and mass.

## Obsticles
Obtaining and cleaning the data was my biggest challenge.

## Learnings
The data visualizations show many learnings, such as:
1) More than half of the satellites we lauched into space are no longer operational. This can in many cases lead to space debris (Idea for future research)
2) Only seven countries in Africa own a satellite
3) The Falcon 9 rocket has been used for the most satellite launches into space (most of which in lower orbit), while Ariane 5 is in fifth place in terms of total launches, but number one for satellites with geostationary orbit
4) Close to three quarters of all active satellites are in lower orbit
5) Around three quarters of all active satellites are use for communication and earth observation
