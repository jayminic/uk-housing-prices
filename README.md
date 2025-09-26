# UK Housing Price Trends (2020–2024)

## 📌 Project Overview
This project analyses the UK Land Registry **Price Paid Data** to explore housing price trends over the last 5 years (2020–2025).  
It is designed as a portfolio project to showcase skills in **SQL, Python, and data visualisation**, starting with core exploratory analysis and extending to more advanced techniques as my learning progresses.

## 🎯 Objectives
- Clean and prepare the Price Paid dataset for analysis.
- Explore trends in housing prices by **year, county, and property type**.
- Compare regional growth rates and identify the fastest- and slowest-growing areas.
- Build clear visualisations to communicate insights effectively.
- Create a reproducible workflow combining **PostgreSQL + Python (pandas, matplotlib)**.

## 🛠️ Tech Stack
- **Database:** PostgreSQL (schema design, indexing, analytical SQL)  
- **Programming:** Python (pandas, matplotlib, SQLAlchemy)  
- **EDA & Reporting:** Jupyter Notebooks (VS Code)  
- **Version Control:** Git & GitHub  

## 📂 Repository Structure
```bash
uk-housing-project/
├── data/ # raw CSV files (ignored in Git)
├── sql/ # schema, indexes, queries
├── notebooks/ # Jupyter notebooks for EDA
├── src/ # optional: Python helper scripts
├── outputs/ # charts and tables for reporting
├── requirements.txt # Python dependencies
├── README.md # project documentation
└── .gitignore # excludes data, venv, etc.
````

## 📊 Example Questions to Answer
- How have average UK house prices changed between 2020–2025?  
- Which counties saw the fastest growth in property values?  
- Which property type (detached, semi-detached, terrace, flat) grew the most in value?  
- Are there seasonal patterns in transaction volumes?  

## 📈 Planned Deliverables
- SQL scripts for data loading, indexing, and core queries.  
- Python notebooks with EDA, visualisations, and commentary.  
- Charts and summary insights exported to the `outputs/` folder.  
- (Future) Dashboard or advanced modelling to extend the project.  

## 📑 Data Source
UK Land Registry – [Price Paid Data](https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads)  
Dataset includes residential property sales in England and Wales from 1995 onwards.  

> ⚠️ **Note:** Due to dataset size, raw CSV files are not included in this repo.  
Please download them directly from the official source.  

## 🚀 How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/uk-housing-project.git
   cd uk-housing-project
   ````
2. Set up a virtual environment and install dependencies:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   source .venv/bin/activate  # Mac/Linux
   pip install -r requirements.txt
   ````
3. Create a PostgreSQL database called housing and load the Price Paid CSV.
4. Run the SQL scripts in sql/ to create schema and indexes.
5. Open the notebooks in VS Code and explore the analysis.
