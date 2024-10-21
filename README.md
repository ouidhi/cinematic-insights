## Exploratory Data Analysis of Movie Production Companies 

### Objective

Conducted an exploratory data analysis on a dataset of global movie production companies to uncover trends in company establishment, geographic distribution, and market concentration. Utilized Python libraries such as Pandas and Seaborn to derive insights and visualize data.
#
### Table of Contents:

1. Questions to answer
2. Key Skills and Tools Used
3. Scraping data from wikipedia
4. Data preparation and cleaning 
5. Understanding the data
6. Data Explorations
7. Results and Conclusion
8. Data Sources
#
### Questions to answer

- Which country has the most film companies? <br>

- What is the trend of company establishment over the years? <br>

- Where are most film companies headquartered? <br>

- What is the average lifespan of these companies? <br>
# 
### Key Skills and Tools Used
   
   **Programming Languages:** Python <br>
   
   **Skills:** Web scraping, data preparation, visualization and analysis. <br>
   
   **Libraries:** Pandas, BeautifulSoup, Matplotlib and Seaborn. <br>
   
   **Data Visualization:** Histograms, count plots and bar charts. <br>
   
   **Other tools used:** Visual Studio Code, GitHub
#
### Scraping data from wikipedia

   [scrap.ipynb](https://github.com/ouidhi/cinematic-insights/blob/e20cf1fd456a1b9c0428bc1ec6676c4cd3694ae4/scrap.ipynb)

   This Jupyter Notebook demonstrates the process of scraping data from Wikipedia using the Beautiful Soup library in Python. The notebook covers the following     key steps: <br>

   **Importing Libraries:** The necessary libraries, including requests and 'BeautifulSoup', are imported to facilitate web scraping. <br>

   **Fetching Data:** A specific Wikipedia page is accessed, and its HTML content is retrieved using the 'requests' library. <br>

   **Parsing HTML:** Beautiful Soup is used to parse the HTML content, allowing for easy navigation and extraction of relevant data. <br>

   **Data Extraction:** Specific elements, such as tables or lists of movie production companies, are identified and extracted from the parsed HTML. <br>

   **Output:** The final dataset is saved as a csv file, providing a structured       view of the scraped information. 

  https://github.com/ouidhi/cinematic-insights/blob/3d9818fa257e3b2efeb8045fa2af88592d284cd7/Productions.csv

#
### Understanding the data

   This table provides a list of film production companies, detailing key information such as the company name, country of origin, headquarters location, year of establishment, and any relevant notes. 

   **Company**: The name of the film production company. <br>
   
   **Country**: The country where the company is based. <br>
   
   **Headquarters**: The specific city or region where the company is headquartered. <br>
   **Est.**: The year the company was founded. The data is collected for companies established between 1893 and 2019. <br>
   **Notes**: Any additional relevant information about the company (e.g., a focus on specific genres like Christian films).
#
### Data preparation and Exploration

   [ExploratoryAnalysis.ipynb](https://github.com/ouidhi/cinematic-insights/blob/38e3a5224d371470e297783f0ac72ad87afea6be/ExploratoryAnalysis.ipynb) 

   This section focuses on cleaning and preparing the scraped data for analysis. The key steps include:

   **Handling Missing Values:** Missing or incomplete data points are identified and managed by either filling or removing them based on the context.

   **Data Type Conversion:** Columns are converted to appropriate data types (e.g., strings, integers, or dates) to ensure consistency.

   **Creating New Features:** New columns are created by extracting relevant information (e.g., calculating the age of companies based on establishment date).

   This preparation ensures the data is clean, structured, and ready for in-depth analysis and visualizations.

   **Exploratory Data Analysis (EDA)**

   This section dives into the initial exploration of the cleaned dataset to understand its structure and key characteristics. Key aspects covered include:

   **Data Summary:** Overview of the dataset, including the shape, column names, and basic statistical summaries.

   **Distribution Analysis:** Examining the distribution of key variables such as company establishment years, headquarters locations, and the number of companies per country.

   **Visualization:** Creating graphs provides a foundational understanding of the dataset, highlighting key trends, patterns, and insights.
#
### Results and Conclusion

### Which country has the most film production companies?
From the analysis, the United States leads with the highest number of film production companies, followed by India and China. On the opposite end, countries like Greece, Indonesia, and Ukraine have the fewest production companies.

![company_country](https://github.com/user-attachments/assets/edac8b3f-5df4-437d-bf9f-4581adc8b1f0)


### What is the trend of company establishment over the years?
The trend of company establishment has fluctuated significantly. There was a steady increase from the 1800s to 1920, followed by a decline between 1920 and 1960. Another sharp rise occurred from 1960 until 2000, peaking in 2000 with the highest number of companies established, after which there has been a gradual decline.

![trend](https://github.com/user-attachments/assets/7745c340-a4cd-46e2-994c-27e145e744e2)


### Where are most film companies headquartered?
Interestingly, despite the United States having the most film companies, Mumbai, India, holds the title for the city with the most company headquarters. This concentration of headquarters in Mumbai contrasts with the broader distribution of company headquarters across various cities in the U.S., such as Los Angeles and New York. Other significant locations include London (UK) and Shanghai (China), highlighting a regional concentration of production companies in these key cities.

![headquarters](https://github.com/user-attachments/assets/9a6ca780-4437-4d4b-a7df-78cbd3cd7af0)

### What is the average lifespan of these companies?
The average lifespan of film production companies is approximately 49.75 years. The oldest company, Edison’s Black Maria (131 years old), originated in the United States, followed closely by Gaumont Film Company from France (129 years old). The United States and France dominate the top five oldest companies.

![oldest](https://github.com/user-attachments/assets/60bb4084-5a27-472b-9629-8432c440aeae)

In contrast, the newest companies, such as Apple Studios, Sight & Sound Films, and Called Higher Studios, are all based in the United States, with many of these companies being around 5 years old. 

![newest](https://github.com/user-attachments/assets/db042dd8-2b24-4ed6-bb95-31442cf19a10)


### Key Insights
- The United States has been consistently dominant in the film production industry, both historically and currently.
- India and China follow as major players, with India’s film headquarters largely centralized in Mumbai.
- London and Shanghai are key cities for film production company headquarters in the UK and China, respectively.

Overall, the analysis underscores the prominence of the United States in the global film industry, with India and China making significant contributions as well.
#
### Data Sources

Wikipedia page: https://en.wikipedia.org/wiki/List_of_film_production_companies




   



