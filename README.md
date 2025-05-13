# COVID-19 Global Data Tracker – README

📝 Project Description:
This project is a data analysis notebook that tracks the global impact of COVID-19 using real-world datasets. It includes data exploration, cleaning, visualization, and key insights about cases, deaths, and vaccinations across countries.

📈 Objective:
- Load and clean global COVID-19 data
- Analyze time-series trends (cases, deaths, vaccinations)
- Compare country-specific metrics
- Visualize data with charts and maps
- Summarize findings with narrative insights

📁 Project Structure:
```
├── covid19_data_tracker.ipynb     ← Main Jupyter Notebook
├── owid-covid-data.csv            ← Dataset (Our World in Data)
└── README.txt                     ← Project documentation (this file)
```

📦 Requirements:
- Python 3.7+
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- plotly (optional, for map visualization)

🛠️ Installation Instructions:
1. Clone or unzip the project folder.
2. Make sure Python and Jupyter are installed.
3. (Optional) Create a virtual environment:

``` powershell
python -m venv venv
source venv/bin/activate # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```
 4. Open the notebook:
```
jupyter notebook covid19_data_tracker.ipynb
```


📂 Dataset:
The data used is from [Our World in Data](https://ourworldindata.org/covid-cases), provided in `owid-covid-data.csv`. This dataset includes daily records of COVID-19 cases, deaths, and vaccinations by country.

🌍 Visualizations Include:
- Line charts of case and death trends
- Daily new case comparisons
- Vaccination progress over time
- (Optional) Choropleth map of cases or vaccinations by country

📌 Insights Section:
The notebook ends with a narrative summary of trends and notable findings across countries.

