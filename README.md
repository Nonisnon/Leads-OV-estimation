# Data Project README file

My project README file
Image

Name
Leads OV estimation


🏃 One-liner
There are 2 different datasource involved:

Deliveroo restaurants data with avg order volume per week

Tripadvisor web Scraping. 


💻 Technology stack
Python, Pandas, BeautifulSoup, Argparse, H2o, geocode by google

💥 Core technical concepts and inspiration
Our main object is to estimate the order volume of the restaurants that we don't have in deliveroo to make easier the business developments work
🔧 Configuration
Requirements:

Path: data/raw/raw_data_project_m1.db
URL: https://ec.europa.eu/eurostat/statistics-explained/index.php/Glossary:Country_codes
Libraries:

You can check it in requirements.txt
📁 Folder structure
└── project
    ├── data
        ├── raw
            ├──.db
    ├── processed
    ├── results
        ├── data_grouped
    ├── notebooks
    │   ├── data,api,webscraping.ipynb
    │   └── Function tables.ipynb
    ├── p_acquisition
        ├── m_acquisition.py
    ├── p_analysis
        ├── m_analysis.py
    ├── p_reporting
        ├── m_reporting.py
    ├── p_wrangling
        ├── m_wrangling.py
    ├── .env.txt
    ├── .gitignore
    ├── main_script.py
    ├── README.md
    ├── requirements.txt

💌 Contact info
If you have any doubts contact me through antoniodediegosuanzes@gmail.com
