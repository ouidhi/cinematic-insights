# cinematic-insights

## Exploratory Data Analysis of Movie Production Companies 

### Objective

Conducted an exploratory data analysis on a dataset of global movie production companies to uncover trends in company establishment, geographic distribution, and market concentration. Utilized Python libraries such as Pandas and Seaborn to derive insights and visualize data.

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
1. **Questions to answer**

- Which country has the most film companies? <br>
- What is the trend of company establishment over the years? <br>
- Where are most film companies headquartered? <br>
- What is the average lifespan of these companies? <br>
# 
2. **Key Skills and Tools Used**
   
   Programming Languages: Python <br>
   Skills: Web scraping, data preparation, visualization and analysis. <br>
   Libraries: Pandas, BeautifulSoup, Matplotlib and Seaborn. <br>
   Data Visualization: Histograms, count plots and bar charts. <br>
#
3. **Scraping data from wikipedia**
   
   This Jupyter Notebook demonstrates the process of scraping data from Wikipedia using the Beautiful Soup library in Python. The notebook covers the following     key steps: <br>

   **Importing Libraries:** The necessary libraries, including requests and 'BeautifulSoup', are imported to facilitate web scraping. <br>

   **Fetching Data:** A specific Wikipedia page is accessed, and its HTML content is retrieved using the 'requests' library. <br>

   **Parsing HTML:** Beautiful Soup is used to parse the HTML content, allowing for easy navigation and extraction of relevant data. <br>

   **Data Extraction:** Specific elements, such as tables or lists of movie production companies, are identified and extracted from the parsed HTML. <br>

   **Output:** The final dataset is saved as a csv file, providing a structured view of the scraped information.

   The notebook: [Uploading scrap.ipynb…]()
#
4. **Understanding the data**

   This table provides a list of film production companies, detailing key information such as the company name, country of origin, headquarters location, year      of establishment, and any relevant notes. 

   **Company**: The name of the film production company. <br>
   **Country**: The country where the company is based. <br>
   **Headquarters**: The specific city or region where the company is                headquartered. <br>
   **Est.**: The year the company was founded. The data is collected for             companies established between 1893 and 2019. <br>
   **Notes**: Any additional relevant information about the company (e.g., a         focus on specific genres like Christian films).
#
5. **Data preparation and Exploration**

   [Uploading ExploratoryAnalysis.ipynb…]()

   This section focuses on cleaning and preparing the scraped data for analysis. The key steps include:

   **Handling Missing Values:** Missing or incomplete data points are identified and managed by either filling or removing them based on the context.

   **Data Type Conversion:** Columns are converted to appropriate data types (e.g., strings, integers, or dates) to ensure consistency.

   **Creating New Features:** New columns are created by extracting relevant information (e.g., calculating the age of companies based on establishment date).

   This preparation ensures the data is clean, structured, and ready for in-depth analysis and visualizations.

   **Exploratory Data Analysis (EDA)**

   This section dives into the initial exploration of the cleaned dataset to understand its structure and key characteristics. Key aspects covered include:

   **Data Summary:** Overview of the dataset, including the shape, column names, and basic statistical summaries.

   **Distribution Analysis:** Examining the distribution of key variables such as company establishment years, headquarters locations, and the number of            companies per country.

   **Visualization:** Creating graphs provides a foundational understanding of the dataset, highlighting key trends, patterns, and insights.
#
6. **Results and Conclusion**

- Which country has the most film companies? <br>
From the count plot, USA has the most film production companies following is india then China. 
Countries with the least fim production companies include Greece, Indonesia, Ukraine and many more. 

- What is the trend of company establishment over the years? <br>
The general trend is fluctuating increasing and then decreasing alternately with increase from 1800 to 1920 then a decrease from 1920 to 1960, again rapid increase till 2000, being maximum companies established in 2000, then again decline till 2019 and so on.

- Where are most film companies headquartered? <br>
Mumbai maharashtra has the most production companies in the world. it is interesting to see that USA has the highest number of production companies but mumbai has the most number of headquarters, which goes to show that most of the headquarters in india are based in mumbai that is concentrated in one city. while there are more than one prominent headquarters in USA based companies that is more widespread in the country. los angeles is next followed by new york in USA. 

second is london while the country in general is on 4. shanghai is the next headquarter, while china was number 3. this means that although china in general has more production companies, and UK has less China but most of the companies in UK have their headquarter in london. most of companies in china have their headquarters in shanghai.

- What is the average lifespan of these companies? <br>
the average age of the production companies is 49.75 years.

Top 10 oldest companies include Edison's Black Maria which is 131 years old and orginated in the United States. It is followed by 129 years old Gaumont Film Company based in France. The top 5 oldest companies are based in United States and France. 

The newest companies include 5 year 
                     Company  Age        Country
329     Edison's Black Maria  131  United States
92      Gaumont Film Company  129         France
373            Lubin Studios  128  United States
410  Selig Polyscope Company  128  United States
93                     Pathé  128         France
441        Vitagraph Studios  127  United States
187         Yoshizawa Shōten  127          Japan
99               Rialto Film  127        Germany
371     Limelight Department  126      Australia
186            Yokota Shōkai  123          Japan
   



