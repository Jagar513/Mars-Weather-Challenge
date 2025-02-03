# Mars Weather Challenge

## Background
This project involves web scraping and data analysis. You will scrape Mars-related news articles and weather data from static web pages, analyze this data, and produce insights.

## Outcomes

1. **Scrape Titles and Preview Text from Mars News Articles**  
   - Scrape titles and preview text from the provided Mars news webpage.
   
2. **Scrape and Analyze Mars Weather Data**  
   - Extract and analyze weather data from the Mars weather table.
   - The data should be cleaned and visualized for insights.

## Files

### Part 1: Mars News  
- **Source URL:** [Mars News](https://static.bc-edx.com/data/web/mars_news/index.html)  
- **Task:** Scrape titles and preview text from Mars news articles using Splinter and BeautifulSoup.

### Part 2: Mars Weather  
- **Source URL:** [Mars Weather](https://static.bc-edx.com/data/web/mars_facts/temperature.html)  
- **Task:** Scrape and analyze weather data from the table, focusing on temperatures and atmospheric pressure.

---

## Steps Taken

### Part 1: Mars News  
- **Automated Browsing:** Used Splinter to automate browsing and extract HTML.
- **Data Extraction:** Employed BeautifulSoup to parse and extract article titles and preview texts.
- **Data Structure:** Stored the data as a list of dictionaries, ensuring each article’s title and preview text were captured.

### Part 2: Mars Weather Analysis  
- **Data Extraction:** Extracted the weather data table from the provided webpage.
- **Data Analysis:** Cleaned the dataset using Pandas and analyzed key metrics, including:
  - Monthly temperature and pressure trends
  - Visualization of temperature patterns
- **Key Insights:**  
  1. There are **12 months** on Mars.
  2. Data is available for **12 Martian months** (sols).
  3. **Coldest month**: Month 3; **Warmest month**: Month 8.
  4. **Lowest atmospheric pressure**: Month 6; **Highest pressure**: Month 9.
  5. A Martian year is approximately **687 Earth days**.

---

## Key Findings

### 1. Number of Mars Months  
There are **12 months** on Mars, each with specific weather and atmospheric data.

### 2. Martian Days (Sols)  
The dataset contains data for **12 Martian months**, each corresponding to one Martian year.

### 3. Coldest and Warmest Months  
- **Coldest month:** Month 3  
- **Warmest month:** Month 8  
The average minimum daily temperature was calculated for each month.

![image](https://github.com/user-attachments/assets/08c8ae4f-5cee-4dc6-b35d-9a48e41fe971)


### 4. Atmospheric Pressure Trends  
- **Lowest pressure:** Month 6  
- **Highest pressure:** Month 9  
These findings help us understand the Martian weather system’s behavior.

![image](https://github.com/user-attachments/assets/8c045eb3-8693-4e1b-ac70-8397a699d0c5)


### 5. Earth Days in a Martian Year  
A Martian year lasts approximately **687 Earth days**, which was confirmed by visualizing the temperature trends.

![image](https://github.com/user-attachments/assets/a889b273-b75f-48d4-8926-2868af383034)

---

## Analysis

### 1. Which month, on average, has the lowest temperature? The highest?

The coldest month on Mars is month 3 with the lowest average minimum temperature at -83.30729166666667, while the month 8 corresponds to the highest average minimum temperature at -68.38297872340425.
These temperature changes are mainly caused by Mars' orbital rotation around the Sun, which creates seasons similar to those on Earth. 
The bar plots visualize these extremes, where the lowest bar indicates the coldest month and the highest bar shows the hottest month.

![image](https://github.com/user-attachments/assets/52186d2e-9980-42fd-9f01-42696a636a6c)

### 2. Which month, on average, has the lowest atmospheric pressure? The highest? 

The month with the lowest average pressure is month 6, while the highest pressure occurs in month 9
The bar chart clearly shows pressure fluctuations across months.

![image](https://github.com/user-attachments/assets/f00fab64-5e2c-4269-8eed-585271f9070f)

### 3. How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. 
To estimate the length of a Martian year in Earth days, the daily minimum temperatures were plotted over time. By identifying repeating seasonal temperature patterns, it was estimated that a Martian year is approximately 687 Earth days. This estimation aligns with established scientific data and falls within a 25% margin of accuracy, reflecting Mars’ distinct seasonal climate cycles.

![image](https://github.com/user-attachments/assets/396e5528-94a4-4612-bb04-1dbaaea17d3f)

