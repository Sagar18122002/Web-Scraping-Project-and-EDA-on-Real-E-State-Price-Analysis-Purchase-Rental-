# Web-Scraping-Project-and-EDA-on-Real-E-State-Price-Analysis-Purchase-Rental-
Real Estate Market Analysis (Purchase vs Rental) using Python. Includes data cleaning, exploratory data analysis, and visualizations to identify price trends, city-wise patterns, builder distribution, and affordable housing insights.


# Real Estate Market Analysis (Purchase vs Rental)

## Project Overview
This project focuses on analyzing the real estate market using data collected through web scraping and exploratory data analysis (EDA). The goal of the project is to understand price trends, location preferences, builder distribution, and affordability patterns across different cities.

The analysis compares **property purchase and rental markets** to identify how housing prices vary based on location, area, builder, and other factors.

This project demonstrates practical skills in **web scraping, data cleaning, exploratory data analysis, and visualization using Python.**

---

## Objectives
The main objectives of this project are:

- Collect real estate data using web scraping.
- Clean and preprocess the collected data.
- Perform exploratory data analysis to understand market trends.
- Identify cities with the highest property prices.
- Analyze builder distribution across cities.
- Compare property purchase and rental trends.
- Visualize data insights using graphs and plots.

---

## Technologies Used
The project is implemented using the following technologies:

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **BeautifulSoup**
- **Requests**
- **Jupyter Notebook**

---

## Project Workflow

### 1. Web Scraping
Property data was collected from online real estate platforms using Python libraries such as **Requests** and **BeautifulSoup**. The scraping process extracts important property information such as:

- City
- Area
- Price
- Builder name
- Property type
- Construction status
- Date of construction

The collected data is stored in a structured dataset for further analysis.

---

### 2. Data Cleaning
The raw scraped data contains inconsistencies such as missing values, symbols in price columns, and inconsistent formatting.

The following preprocessing steps were performed:

- Removing special characters from price values.
- Converting prices into numerical format.
- Handling missing values.
- Standardizing column names.
- Formatting date values.

This step ensures the dataset is suitable for analysis.

---

### 3. Exploratory Data Analysis (EDA)

Exploratory data analysis is performed to understand patterns and relationships within the data.

Different types of visualizations were used:

#### Distribution Analysis
- Price distribution across cities
- Area distribution
- Property availability

#### Categorical Analysis
- Builder distribution across cities
- Construction status comparison

#### Multivariate Analysis
- Relationship between city and property price
- Relationship between builder and property distribution

Visualization tools used include:

- Bar charts
- Pie charts
- Heatmaps
- Box plots
- Scatter plots

---

### 4. Key Insights

Some important insights obtained from the analysis include:

- Certain cities have significantly higher property purchase prices.
- Builder distribution varies widely across cities.
- Some areas offer more affordable housing options compared to others.
- Rental markets show different pricing patterns compared to purchase markets.

These insights help understand real estate market behavior.

---

## Project Structure
Real_Estate_Price_Analysis
│
├── data
│ └── real_estate_dataset.xlsx
│
├── notebooks
│ ├── web_scraping.ipynb
│ ├── data_cleaning.ipynb
│ └── eda_analysis.ipynb
│
├── images
│ └── visualizations
│
└── README.md


---

## Visualizations
The project includes multiple visualizations that help understand the real estate market.

Examples include:

- City-wise property price distribution
- Builder vs city analysis
- Price comparison between purchase and rental markets
- Correlation heatmap of numerical variables

---

## Conclusion
This project demonstrates how data analysis techniques can be applied to real estate datasets to uncover meaningful insights. By combining web scraping with exploratory data analysis, it is possible to understand market trends and identify factors influencing housing prices.

The project also highlights the importance of data preprocessing and visualization in deriving useful information from raw datasets.

---

## Future Improvements
Possible improvements for the project include:

- Expanding the dataset to include more cities.
- Adding machine learning models for price prediction.
- Creating an interactive dashboard for real estate insights.
- Automating the data collection process for real-time analysis.

---

## Author
**Dandoti Sagar**

Electronics and Communication Engineering  
Data Analysis & Python Enthusiast
