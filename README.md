# data-512-a1
Data 512 A1:_Data_curation
Thomas Winegarden

# Goal of the Project
This README is part of assignment 1 of the class Human Centered Data Science (DATA 512) at The University of Washington. Assignment requirements can be found here: https://wiki.communitydata.science/Human_Centered_Data_Science_(Fall_2019)/Assignments#A1:_Data_curation

"The purpose of the assignment is to demonstrate that you can follow best practices for open scientific research in designing and implementing your project, and make your project fully reproducible by others: from data collection to data analysis." - Jonathan Morgan (JMO), DATA 512 (FALL 2019): A1

# Data Use & Licensing
https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

This project project is available under an MIT license.

# API Docs
Two different APIs provided by wikimedia were used.

Legacy Page Count: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts

Page Views: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

# Final field values
The repo contains 5 JSON files from

The repo also contains a munged .csv of the final data.

Columns: year (YYYY), month (MM), pagecount_all_views (float), pagecount_desktop_views (float), pagecount_mobile_views (float), pageview_all_views (float), pageview_desktop_views (float), pageview_mobile_views (float)

year	YYYY
month	MM
pagecount_all_views	num_views
pagecount_desktop_views	num_views
pagecount_mobile_views	num_views
pageview_all_views	num_views
pageview_desktop_views	num_views
pageview_mobile_views	num_views


# Important things to note

Data after 2015 within the page views API does not include scrapers or web crawler views on wikipedia.

The notebook uses Python version 3.7.1


