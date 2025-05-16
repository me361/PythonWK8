# PythonWK8

📊 COVID-19 Global Data Analysis & Visualization
This project explores and visualizes COVID-19 global data using the Our World in Data dataset. It covers cases, deaths, vaccinations, and trends using Python (pandas, matplotlib, seaborn, and plotly) in a well-documented Jupyter Notebook.

✅ Project Goals
Load and explore real-world COVID-19 data.

Clean and prepare data for analysis.

Generate insights and trends for selected countries.

Visualize key metrics using plots, heatmaps, and choropleth maps.

Summarize findings through visual storytelling.

📁 Dataset Source
Source: Our World in Data – COVID-19 dataset

File used: owid-covid-data.csv

Latest date available: 2024-08-14

Most recent valid data used: 2024-08-04

🛠️ Tools & Libraries
Python 3.x

pandas

matplotlib

seaborn

plotly.express (for interactive maps)

Jupyter Notebook

🔎 Key Steps
1. Data Loading
Loaded the CSV file using pandas.read_csv().

Displayed column names and previewed the first few rows.

2. Data Cleaning
Filtered key countries (e.g., Kenya, USA, India, etc.).

Dropped missing or irrelevant rows.

Converted date to datetime format.

Handled missing values via fillna() or filtering.

3. Exploratory Data Analysis (EDA)
Line charts for total cases and total deaths over time.

Calculated and printed death rates per country.

Visual comparison of daily new cases.

4. Vaccination Analysis
Line chart showing total vaccinations over time.

Bar chart comparing % of population fully vaccinated.

5. Heatmap
Correlation heatmap of metrics like:

Total cases

Deaths

Vaccination stats

6. Choropleth Maps
Interactive global maps using Plotly:

Total cases by country

% of population fully vaccinated

📌 Key Insights
Most countries report fewer or no new cases after mid-2024.

Vaccination rates vary greatly across regions.

Strong correlation between total cases and deaths.

Some countries achieved high vaccination coverage by 2024.

