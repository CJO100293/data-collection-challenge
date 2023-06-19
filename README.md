# data-collection-challenge
## **Background:**

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

This new assignment consists of two technical products. You will submit the following deliverables:
- Deliverable 1: Scrape titles and preview text from Mars news articles.
- Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

## **Sources:**
### **Part 1:**
- The starter code used in the "Install the needed dependencies", "Import additional dependencies required for code" and the "Changing "browser = Browser('chrome')" to the following to run it better." sections of "part_1_mars_news.ipynb" was worked out with the assistance of AskBCS.
- The basis for the code used in the # Loop through the text elements, Extract the title and preview text from the elements, Store each title and preview pair in a dictionary, Add the dictionary to the list" section was worked out in collaberation with Tyler White along with the assistance of AskBCS.
- The basis for the code found in my "Saving scraped data to json file" section was found from https://medium.com/@wilirahmatm/extract-data-from-web-scraping-to-csv-and-json-files-using-python-705700cac050.
### **Part 2:**
- The starter code used in the "Install the needed dependencies", "Import additional dependencies required for code" and the "Changing "browser = Browser('chrome')" to the following to run it better." sections of "part_2_mars_weather.ipynb" was found from the same source as the same section of Part 1.
- AskBCS suggested/helped with the separate bit of code in the "#Extract all columns" section of the "Step 2: Scrape the Table" portion in "part_2_mars_weather.ipynb" for grabbing the columns instead of manually adding the column names into the dataframe in the "Create a Pandas DataFrame by using the list of rows and a list of the column names" section later on.
- The basis for the code used in the "Create an empty list to contain the columns data", "Loop through the scraped data to create a list of columns", "Create an empty list to contain the row data" and "Loop through the scraped data to create a list of rows" section of the "Step 2: Scrape the Table" portion in "part_2_mars_weather.ipynb" was worked out with the assistance of Tyler White and AskBSC as well as https://www.programiz.com/python-programming/methods/string/strip.