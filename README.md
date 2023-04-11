# Module_11_challenge

In this challenge I´ll identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.

This new assignment consists of two technical products. You will submit the following deliverables:

* Deliverable 1: Scrape titles and preview text from Mars news articles.

* Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

# Part 1: Scrape Titles and Preview Text from Mars News

In this part I´ll use automated browsing to visit the Mars news site and  inspect the page to identify which elements to scrape. For this I´ll use splinter and BS4 to extract the elements from the web.

Then I´ll extract the titles and preview text of the news articles that I scraped and store the scraping results in Python data structures. For this I´l look for all the text element that conatins "list_text" , then I´ll create an empty list and I´ll store all the dictionaries in a Python list.

# Part 2: Scrape and Analyze Mars Weather Data 

Here as well as in part 1 I´ll use automated browsing to visit the Mars Temperature Data Site and inspect the page to identify which elements to scrape.

I used Beautiful Soup object and use it to scrape the data in the HTML table.

I got the following columns and plot some Mars behaivors using matplotlib.pyplot

* id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
* sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
* ls: the solar longitude
* month: the Martian month
* min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
* pressure: The atmospheric pressure at Curiosity's location


Finally I exported  the DataFrame to a CSV file.

References
The Mars News website is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars News website in November 2022. Images are used according to the JPL Image Use Policy, courtesy NASA/JPL-Caltech.



