# Flipkart Televisions Data Analysis  
This project involves collecting, cleaning, and analyzing data of televisions listed on the Flipkart website. The process includes web scraping, data cleaning, and exploratory data analysis (EDA) to gain insights into pricing trends, brand popularity, and feature analysis.

---

## Project Workflow  
### Step 1: Data Collection (Web Scraping)  
- Used **BeautifulSoup** to scrape television data from Flipkart.  
- Extracted key details:  
  - **Brand**  
  - **Screen-Size**  
  - **Resolution**  
  - **Display-Type**  
  - **Operating-System**  
  - **Rating**
  - **Number of Ratings**
  - **Reviews**
  - **Price**
  - **Original Price**
  - **Discount**   

### Step 2: Data Cleaning  
- Removed duplicate entries and handled missing values.  
- Converted columns to appropriate data types for consistency.  
- Cleaned and standardized categorical values.

### Step 3: Exploratory Data Analysis (EDA)  
- **Univariate Analysis**: Distribution and summary statistics of individual variables.  
- **Bivariate and Multivariate Analysis**: Relationships between different variables, including:  
  - **Numerical vs Categorical**  
  - **Numerical vs Numerical**  
  - **Categorical vs Categorical**  

### Tools and Libraries Used  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Web Scraping**: BeautifulSoup  
- **Data Visualization**: Matplotlib, Seaborn  
- **Jupyter Notebook**: For interactive data exploration and analysis  

---

## Repository Structure  
- `Flipkart Televisions Data Analysis.ipynb`: Jupyter notebook containing the entire data collection, cleaning, and analysis process.  
- `flipkart_televisions.csv`: Raw data collected from Flipkart.  
- `televisions_flipkart_cleaned.csv`: Cleaned and processed data used for analysis. 
