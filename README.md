# Mission to Mars

## Overview of the project

- The purpose of the analysis is to scrape, organize, analyze, and visualize the data.

## Sources

- Data: 
    1. [Mars NASA news site](https://redplanetscience.com)
    2. [mars-challenge](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html)

- Softwares: Python 3.7(Splinter and BeautifulSoup), Jupyter Notebook 6.4

## Analysis

### Part 1(Scrape titles and preview text from Mars news articles)

- The link to the script of the analysis is : [Mars_News](https://github.com/manasidek/Mission_to_Mars/blob/main/Starter_Code/part_1_mars_news.ipynb)

- The image of the scraping is shown below:

![title_preview](https://github.com/manasidek/Mission_to_Mars/blob/main/images/title_preview.png)

- The link to the output file is [mars_news](https://github.com/manasidek/Mission_to_Mars/blob/main/Starter_Code/mars_news.txt)

### Part 2 (Scrape and Analyze Mars Weather Data)

- The link to the script of the analysis is : [Mars_Weather](https://github.com/manasidek/Mission_to_Mars/blob/main/Starter_Code/part_2_mars_weather.ipynb)

- The data from scraping is stored in a dataframe, which is shown in the image below :

![DataFrame](https://github.com/manasidek/Mission_to_Mars/blob/main/images/DataFrame.png)

- The data was analyzed and visualization was created:

    1. The Average Temperature per month was calculated.
    
    ![Avg_Temp_month](https://github.com/manasidek/Mission_to_Mars/blob/main/images/Avg_temp_month.png)
    
    2. The Sorted visualization of average temperature is shown below:
    
    ![Sorted_avg_temp_month](https://github.com/manasidek/Mission_to_Mars/blob/main/images/Sorted_avg_temp_month.png)

    3. The Average Pressure per month was calculated.
    
    ![Avg_pressure_month](https://github.com/manasidek/Mission_to_Mars/blob/main/images/Avg_pressure_month.png)
    
    4. The number of terrestrial days in a martian year.
    
    ![terrestrial_days](https://github.com/manasidek/Mission_to_Mars/blob/main/images/terrestrial_days.png)

- The link to the output file is [Mars_Weather_data](https://github.com/manasidek/Mission_to_Mars/blob/main/Starter_Code/Mars_Weather_data.csv)

### Summary

- On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!

- Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.

- The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot.