# Amazon_Vine_Analysis

Overview

The purpose of this analysis was to create data frames using AWS and RDS from information chosen from Amazon datasets.  I chose to use information from video game reviews.  The analysis used google colab and Pyspark to extract data.  AWS, RDS connected the extracted data to pgAdmin which was used to create various tables.  


Results

Total Reviews

![Total Vine Reviews](https://user-images.githubusercontent.com/92127589/152852358-7b794bbf-7d2c-496f-b955-2a91e29dd4ca.PNG)
![Total Non-Vine reviews](https://user-images.githubusercontent.com/92127589/152852380-fa4a004c-8e6d-4c4a-af39-1be9adccf128.PNG)

5 Star Reviews

![5 star vine reviews paid](https://user-images.githubusercontent.com/92127589/152852415-a48a8cea-7330-49d0-a26c-dafe26bb6498.PNG)
![5 star non vine reviews unpaid](https://user-images.githubusercontent.com/92127589/152852431-eae4b2fc-1861-4e69-8e1d-4666d13e1801.PNG)

Percentage of 5 Star Reviews

![Percentage of 5 star reviews paid](https://user-images.githubusercontent.com/92127589/152852491-f4f1fcd6-76a3-4f04-ac1f-0e76cc0e5ce7.PNG)
![Percentage of 5 star reviews unpaid](https://user-images.githubusercontent.com/92127589/152852506-d7c97d4a-560b-4baa-8ee1-45d448d21843.PNG)

Summary

Based on the results 51% of the reviews were paid 5-star reviews compared to 39% for unpaid 5 star reviews.  This shows that if a review was paid the higher chance they were going to give a 5 star review demonstrating a positivity bias for reviews.  An additional analysis could be reviews where with no paid reviews at all.  You could also analyze stats showing the star ratings that are less than 5 stars.      
