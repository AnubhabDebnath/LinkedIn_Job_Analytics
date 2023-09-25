# 
# <img src="https://media.tenor.com/2ZexrTx-QSQAAAAC/linkedin.gif" width="48" height="48"> **Introduction**

This depository contains the analysis of all the jobs available at linkedin website, it goes through various stages and during the process has encountered a few problems. By tackling those problems I have successfully got a few insights which will help potential job seekers and recruiters to get their best fit. The data scraping part was done in python, cleaning was done using excel and the queries needed were run using mysql again the final dashboard was made on excel.



<img src="https://media.tenor.com/KOki-OrS24AAAAAC/linkedin.gif" width="1000" height="700">

  
# <img src="https://media.tenor.com/WMS0HHtKYD8AAAAi/handwerk-stephaniebergerschmuck.gif" width="48" height="48"> **Tools Used**
![Screenshot 2023-05-13 205703](https://github.com/AnubhabDebnath/LinkedIn_Job_Analytics/assets/110715196/d2ba0355-fb9f-4665-b79e-a6f7dd1735c5)



# <img src="https://media.tenor.com/WMS0HHtKYD8AAAAi/handwerk-stephaniebergerschmuck.gif" width="48" height="48"> **Problems aimed to solve**



Our initial challenge involved extracting data from professional networking platforms such as LinkedIn. These platforms typically have stringent measures in place to prevent easy data scraping, thus precluding the use of straightforward software solutions for this task. Our second task was to ensure the proper processing and thorough cleaning of the raw data. This step was crucial to minimize the presence of outliers and enhance the overall quality of our dataset.



# <img src="https://media.tenor.com/S_MxiWkUAHMAAAAi/steps-baby-steps.gif" width="48" height="48"> **Steps Involved**

There were a few steps involved bofore we got to the analysis part which are as follows:
  1. Scraping the Data from LinkedIn - LinkedIn or similar sites don't want people to get access to their data for obvious resons so we had to find a workaround using BeautifulSoup. We managed to take the relevant information from there and convert it into a dataset in python itself.
  2. Automating the page turner - There was an option in the webpage to turn the page to next in order to get to the data in the second page, we used the help of selenium webdriver here to act as a clicker which clicks the next page button after a specific interval of time.
  3. Cleaning - Altough cleaning was done in excel which didn't involve any coding but still it took a while to decide which data are relevant and which are not. Once done, I moved on to the deleting part where the irrelevant data were deleted. At last I used data cleaning tools from excel to make sense of the data and remove any noise values from it.
  4. Running Queries - We needed to find the solution to a few questions which I did using MySql.
  5. Making the Dashboard - After all of the above tasks were done, I derived a few insights from the data and with the help of pivot tables and then charts I was able to show the visualizations needed.




# <img src="https://media.tenor.com/F7Y9A0SWAUcAAAAi/goal-circle.gif" width="48" height="48"> **Insights**

![image](https://github.com/AnubhabDebnath/LinkedIn_Job_Analytics/assets/110715196/fdcd98d3-67a8-46a5-aa59-880fbe27fd7f)

Here we can clearly see which industries have the highest total number of employees.
Financial Services and IT Services have the highest available jobs in the market right now.


![image](https://github.com/AnubhabDebnath/LinkedIn_Job_Analytics/assets/110715196/39faacd8-59b0-4f77-87a5-9eaba4856428)

In the above chart I took 5 different cities from the dataset and compared them on the basis of job count and the different levels they belong to.
Clearly Bangalore has the highest job openings followed by delhi.




# <img src="https://media.tenor.com/ts5y4CC3OlYAAAAC/life-is-so-hard-long-day.gif" width="48" height="48"> **Problems Faced**

The first problem I encountered was with the new libraries that I needed to learn about to pull in data from LinkedIn. I used Selenium and BeautifulSoup to scrape the data, but I had to learn them from scratch and research a lot online in order to use them in my project.The next problem waiting for me was the cleaning of the data. The raw data was really hard to understand and I had to work on it for hours to make it usable and clean.
  1. The first problem was fixed using BeautifulSoup and Selenium WebDriver, I managed to pull the data from LinkedIn using BeautifulSoup and automated the process using Selenium for things like changing the page number etc.
  2. The second challenging problem was solved using excel, I had to use various tools as well as functions to clean the dataset thoroughly as it was a very essential part of our project, specially when the next step was to run queries in sql.




# <imf src="https://media.tenor.com/RUKQWE0MJE4AAAAi/road-sign-roadtrip.gif" width="48" height="48"> **Conclusion**
The scraping, cleaning, querying, and dashboard creation processes were successful in extracting, organizing, and presenting the data in a meaningful way. The resulting dashboard provided valuable insights into the data and allowed for easy analysis and interpretation.

Overall, the project was a success in using Selenium web driver, Beautiful Soup, Excel, and SQL to scrape, clean, query, and analyze data from LinkedIn. The resulting dashboard provided a valuable tool for understanding and interpreting the data.
  

  

# <imf src="https://media.tenor.com/-YcB0iBIq0cAAAAC/learn-learning.gif" width="48" height="48"> **Learnings**
After finishing this project, we came to a few conclusions but also though about how it could be made better if someone wants to do it in the future. We noted down a few pointer which could be remembered while re-doing this project.
  1. We might want to use some alternatives to scrap the data from a website like Scrapy, Selenium, import.io, ParseHub, and Octoparse.
  2. For the cleaning part we can try using Python which would take lesser time than doing it in Excel. 
  3. The Dashboard can be made using PowerBI instead of Excel itself. We would not only have more options but also the visualizations would be much better looking in appearence.
  
