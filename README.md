Structure Fires
Tableau Dashboard
Link:  
Table of Contents
* Tableau Dashboard
* Motivation
* Questions
* Normalizing the Data
* Problems and Hurdles
* Technologies Used
* Sources
* Conclusion
Motivation:
Fires are a significant threat to public safety, and understanding the patterns and trends associated with structure fire incidents is crucial for effective prevention strategies. With close ties to local fire departments in Kentucky, performing an analysis on fires in Nashville stems from a deep concern for community safety and a desire to make a positive impact.  I explored the following:
Questions:
* Is there a structure fire season?
* Do specific fire causes vary per season?
* Does the volume vary per zip code? Do demographics play into the volume?
Normalizing the Data
The dataset I selected mainly consisted of years from 1970 through 2021. I selected the most recent five years of data, 2017-2021. I then cleaned the data and narrowed down to the information that I wanted to use for my analysis. My initial approach was to use the data for Nashville, TN and then compare the difference/ correlation between zip codes, but I realized that it would be more interesting to compare it to the entire state of Tennessee.
Problems and Hurdles
With this analysis containing both public and personal information, it will be difficult to plot fire locations on a map. Protecting citizen’s identities and addresses is top priority while simultaneously providing a deep enough analysis. I initially wanted to see if there were properties experiencing several fires by the same cause, but protecting the persons’ information was crucial.
Technologies Used
1. Python / Pandas - for exploration, normalizing and aggregation of the dataset
2. Tableau - for creating interactive dashboard
3. Git - for version control
Data Sources
To answer the above questions I used the following sources to collect datasets for my analysis
1. Structure Fire information (Nashville, TN and Tennessee) Annual NFIRS Public Data | FEMA.gov
2. Nashville Fire Departments Fire Stations (Map) | Nashville Open Data Portal  
3. Nashville zipcodes/Neighborhoods Nashville Area Zip Codes (nashvillesmls.com)
4. OECD.Stat (Organization for economic co-operation and development) https://data.oecd.org/unemp/unemployment-rate.htm
Conclusion
The data analysis shows the correlation between various structure fire causes and time of year in Tennessee and Nashville. According to the analysis performed, there is a structure fire season (fall) and the causes change volume with the season and zipcode. With the findings of the analysis, valuable insights will be provided for fire departments and the community in Nashville and Tennessee.
