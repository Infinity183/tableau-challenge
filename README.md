# tableau-challenge
For this challenge, I designed a Tableau story with visualizations built using data obtained from the New York Citi Bike website. (https://s3.amazonaws.com/tripdata/index.html) I decided to focus on trends for the year of 2018.

To start, I downloaded the twelve CSV spreadsheets on their website containing information pertaining to 2018 bike rides, with each file pertaining to a specific month of 2018. I then used a Jupyter Notebook Python app to clean and reformat each spreadsheet to my liking. Next, I uploaded all twelve spreadsheets into a new Tableau Desktop project and combined them as a union. Thus, I had big data to work with for all twelve months of 2018.

Using the data I was given, I decided to make calculated fields based on generation in order to categorize bike riders by age more easily. I also made a calculated field that assigned "Female", "Male", or "Unknown" to each case depending on their gender value (according to the website, 0 is for unknown, 1 is for male, and 2 is for female).

With these extra fields added, I proceeded to develop five dashboards that each contain visualizations from which to make insightful conclusions about the given data. I found that there are far more male riders than female riders, middle months and rush hours are the most popular times for bike usage, and areas in southern Manhattan have much heavier bike usage than anywhere else in the city.

NOTE: The anaylsis portion of this assignment is included within the Tableau notebook, with paragraphs accompanying each page of the story.
