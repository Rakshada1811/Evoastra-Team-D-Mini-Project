*Evoastra Team D – Mini Project*

Web Scraping Honda Car Variants from AckoDrive.com

This repository contains the mini-project completed under the Evoastra internship program. The objective was to scrape detailed specifications of Honda car variants from AckoDrive.com using Python, Selenium, BeautifulSoup, and Pandas. The outputs include raw and cleaned datasets, a fully documented notebook, the report, and the final presentation.

Project Overview

The project automates variant-level data extraction from AckoDrive.com. Selenium was used to load interactive elements and navigate through variant pages. BeautifulSoup and regular expressions handled HTML parsing, and Pandas was used for data cleaning and standardization.

*Data Extracted:*
-Model Name
-Variant Name
-Price
-Fuel Type
-Engine Capacity
-Transmission Type
-Mileage
-Seating Capacity

*Technical Stack:*
-Python
-Selenium WebDriver
-BeautifulSoup (bs4)
-Requests
-Regular Expressions
-Pandas
-Google Colab

*Workflow Summary:*
-Fetch Honda model list from AckoDrive.com
-Use Selenium to load all available variants
-Extract specifications for each variant
-Handle dynamic content and irregularities
-Clean and standardize data using Pandas
-Generate raw and cleaned CSV files
-Compile notebook, report, and presentation

*Repository Structure:*
Evoastra-Team-D-Mini-Project/
│
├── notebook/
│   └── Team_D_Honda_Scraper.ipynb
│
├── data/
│   ├── car_variants_raw.csv
│   └── honda_cleaned_data.csv
│
├── report/
│   └── Team_D_Final_Report.pdf
│
├── presentation/
│   └── Team_D_Presentation.pdf
│
└── README.md

*Team Roles:*
*Team Lead:* Rakshada
*Co-Lead:* Subham
*Web Scraping:* Anurag, Nazim, Aravind
*Data Cleaning:* Rakesh, Sai Kiran
*Report Writing:* Subham, Rakshada
*Presentation:* Rakshada
