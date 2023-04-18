# CMPINF0010FinalProject
Final Project for CMPINF0010 Big Ideas.

We were tasked with taking data from the Western Pennsylvania Regional Data Center to determine what the best neighborhood in Pittsburgh is. We selected the metric *best neighborhood to do car racing.*


- Team name: Team Kevin
- Team members and their email addresses
  - Kevin Pak / KEP119@pitt.edu
  - Ryder Pham / RTP26@pitt.edu
  - Alex Malfregeot / AMM635@pitt.edu
  - Zach Lehning / ZAL36@pitt.edu
- Description and links to the datasets used
  - Dataset 1: [Number of speed bumps in Pittsburgh Neighborhoods](https://data.wprdc.org/dataset/city-of-pittsburgh-speed-humps)
    - This data conveys how many speed bumps there are in several Pittsburgh neighborhoods. It is applicable as a metric because we found that more speed bumps lead to a worse experience in street racing. So, we are trying to find the neighborhoods with the least amount of speed bumps.
  - Dataset 2: [Pittsburgh Police Arrest Data](https://data.wprdc.org/dataset/d809c36f-28fe-40e6-a33e-796f15c66a69/resource/e554650d-f48f-49b2-88f3-e19878a1c245/download/arrest-data-dictionary.xlsx)
    - This data relays every arrest made in Pittsburgh. The data includes:
      - Incident and arrest location generalized to a block (police zone for sex crimes) (i.e., Neighborhood)
      - Type of incident
      - Date
      - Time
      - Offender demographics (race, age, gender)
  - Dataset 3: [Traffic Count Data](https://data.wprdc.org/datastore/dump/6dfd4f8f-cbf5-4917-a5eb-fd07f4403167)
      - This dataset contains average car and bicycle traffic in several intersections and roads throughout the neighborhoods of Pittsburgh.
      - The dataset includes entries spanning the past 5 years not including 2023, but I elected to only include entries from Jan 1, 2019 and onward.
      - Some neighborhoods only had one data entry, so I decided to exclude them from my analysis.
      - Many entries had location and zoning information, but no average traffic, so I decided to exclude them as well.
      - I analyzed only recent traffic data from neighborhoods with more than one entry containting an avg. traffic value in order to determing which 'hood' has the least average traffic
      - We are interested in finding the ones with the least amount of traffic, as the last thing you would hopefully want as a street racer is to plow into a Shadyside soccer mom's Cadillac Escalade.
  - Dataset 4: [City of Pittsburgh Crosswalk](https://data.wprdc.org/datastore/dump/632fbb91-c55d-4221-a8ad-91c72902bc61)
      - This dataset contains intersection markings for crosswalk and stop line locations and information. 
      - The data in this dataset has not been updated since 2021 (and 2018 in for crosswalk data)
      - Difficulties surronding this dataset included counting multiple crosswalks at the same intersection which made it less reliable.
    
After comparing our datasets the best neighborhood for Drag Racing was **Highland Park**. To reach this conclusion, Team Kevin compared the number of speedbumps, numbers of arrests, average daily traffic, and number of crosswalks throughout the neighborhoods of Pittsburgh. Speed bumps are weighted heavily; hitting speedbumps at racing speed will kill your suspension and possibly you along with it. Arrests were weighted less heavily, as many in the dataset likely took place off the roads. Traffic figures are weighted heavily for the same reason as the speedbumps. Crosswalks are weighted less heavily than traffic and speedbumps, but still an important metric. Hopefully pedestrians will notice you barreling towards them at highway speeds in the 25 MPH zone and get the heck out of the way. 