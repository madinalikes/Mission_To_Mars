# Mission to Mars
---
![image](https://user-images.githubusercontent.com/111404552/209899032-a909a18b-a97c-4094-8c76-f4e0df6bce90.png)

#### Overview

The mission of this project was to learn web scraping methods to extract information from the NASA Science Mars Exploration website using Chrome Developer tools to identify HTML components, Beautiful Soup/Splinter to automate a web browser and perform the scrape, MongoDB to store the data, and finally Flask to create a web application to display the data. Through the process, the goal was to develop an appt to scrape the following information about the planet Mars:

**Deliverable 1**: Scrape titles and preview text from Mars news articles. Optionally export the data into a JSON file or a MongoDB database.

Using Splinter automated browsing was used to visit the Mars news site. Then, I extracted the HTML code with Beautiful Soup. Next, I have scraped and extracted the titles and preview text of the news articles and stored them in a dictionary.

<img width="617" alt="image" src="https://user-images.githubusercontent.com/111404552/209900344-f28a2799-8256-4eb2-9800-4bb403f7ff77.png">


Finally, I exported the data to JSON file and saved it as mars.csv

To see the full code written in this part check part_1_mars_news.ipynb

**Deliverable 2:** Scrape and analyze Mars weather data, which exists in a table.

Using Splinter automated browsing was used to visit the Mars temperature data site. I have extracted the HTML code with Beautiful Soup. Scraped and extracted the Mars temperature table into a Pandas DataFrame. Next. I have cleaned the table data by editing its data types

After extracting Mars temperature table, I used the table to analyze and visualize the data by finding  answers to the following questions:

-How many months exist on Mars?
-How many Martian (and not Earth) days worth of data exist in the scraped dataset?
-What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
-Which months have the lowest and the highest atmospheric pressure on Mars? 
-About how many terrestrial (Earth) days exist in a Martian year? 

Average Minimum Temperature by Month on a mars.

![image](https://user-images.githubusercontent.com/111404552/209901119-ab907bbd-fcbe-4e50-b4fa-c93956d4764f.png)
