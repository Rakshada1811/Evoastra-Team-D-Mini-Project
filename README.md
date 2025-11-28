Evoastra Team D – Mini Project
Web Scraping Honda Car Variants from AckoDrive.com

This repository contains the mini-project completed as part of the Evoastra internship program. The objective of the project was to scrape variant-level specifications of Honda cars from AckoDrive.com using Python-based automation and data processing tools. The final output includes raw and cleaned datasets, a documented Jupyter notebook, the project report, and the final presentation.

Project Overview

The project automates the extraction of model-wise and variant-wise information for Honda cars. Selenium was used to interact with dynamic web pages and load variant sections, while BeautifulSoup and regular expressions were utilized to parse HTML content and extract structured data. The dataset was then standardized using Pandas and exported for analysis.

Data Extracted

For each Honda car variant, the following fields were collected:

Model Name

Variant Name

Price

Fuel Type

Engine Capacity

Transmission Type

Mileage

Seating Capacity

Technical Stack

Python

Selenium WebDriver

BeautifulSoup (bs4)

Requests

Regular Expressions

Pandas

Google Colab

Workflow Summary

Fetch Honda model list from AckoDrive.com

Load all variants using Selenium interactions

Extract required specifications for each variant

Handle errors, dynamic content, and skipped elements

Clean and standardize the dataset using Pandas

Generate raw and cleaned CSV files

Document the full workflow (notebook, report, presentation)

Repository Structure
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

Team Roles

Team Lead: Rakshada

Co-Lead: Subham

Web Scraping: Anurag, Nazim, Aravind

Data Cleaning: Rakesh, Sai Kiran

Report Writing: Subham, Rakshada

Presentation: Anurag, Rakshada

How to Run the Notebook

Install required dependencies:

pip install selenium beautifulsoup4 pandas requests


Install ChromeDriver compatible with your Chrome version.

Run the notebook in Google Colab or any Jupyter environment.

Generated CSV files will be saved automatically in the /data directory.
