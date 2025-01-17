# Premier League ETL: Scraping to Insights

## Extract  
Extracting data from Premier League webpages was done through **web scraping** with the power of **Scrapy**, ensuring we captured every crucial detail about team performance.

---

## Transform  
Once the raw data was in hand, it underwent an essential transformation using **Python**. This step cleaned and reshaped the data to make it ready for insightful analysis.

---

## Load  
To ensure flexibility and further usability:
- **Dynamic table schema**: Transformed data was loaded into a **SQLite3 database** for structured storage.
- **CSV backup**: Another copy was saved as a CSV file for additional cleaning and analysis.

---

## Insight  
Here’s where the story unfolds:  

1. **Team’s Goal Performance**  
   - Arsenal FC, Liverpool FC, and Manchester United FC top the charts with a goal-scoring average of **1.8 goals per match**.

2. **Team’s Negative Performance**  
   - Arsenal FC holds the dubious honor of leading in negative stats:  
     - **122 Red cards**  
     - **3,545 Fouls**

3. **Team’s Overall Performance**  
   - Dominance on the pitch? It’s **Manchester United FC** with a winning rate of **75.47%**, followed closely by Arsenal FC and Liverpool FC at **71%** each.

---

This end-to-end ETL process shines a spotlight on the glory and pitfalls of the Premier League’s finest teams!
