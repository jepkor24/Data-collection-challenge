# Data-collection-challenge.  
**Data Collection Challenge overview**  
    This new assignment consists of two technical products. You will submit the following deliverables:

   -     **Deliverable 1: Scrape titles and preview text from Mars news articles.**  

   -     -**Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.**  

   - **Part 1: Scrape Titles and Preview Text from Mars News**.  
        -Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).

        -The titles and preview text of the news articles were scraped and extracted.

        -The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries
   - **Part 2: Scrape and Analyze Mars Weather Data**.  
       - The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. 

        -*The data was analyzed to answer the following questions:*

           - How many months exist on Mars? 
           - How many Martian days' worth of data are there? 
           - The data was analyzed to answer the following questions, and a data visualization was created to support each answer: 

           - Which month, on average, has the lowest temperature? The highest? 
           - Which month, on average, has the lowest atmospheric pressure? The highest? 
           -  How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. 
           - The DataFrame was exported into a CSV file.
    - **The files created are as follows:**.  
        - Part_1_mars_news = has analysis for the Part 1 analysis
        - Part_2_mars_weather = has analysis for the Part 2 analysis
        - mars_data = has the output of the dataframe created in a csv file