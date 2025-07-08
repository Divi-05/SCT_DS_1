# SCT_DS_1
=>Top 20 Most Populous Countries (2024)
This Jupyter Notebook uses World Bank data and Python (pandas + Matplotlib) to visualize the twenty most populous countries in 2024.

->Data set
- Top10_Population_2024.ipynb — notebook with step-by-step data loading, cleaning, and chart creation  
- API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv — raw World Bank dataset  
- requirements.txt— dependencies: `pandas`, `matplotlib`, and `jupyter`
  
 -> How to Get Started
1. Launch Jupyter
   jupyter notebook
2. Open `countries.ipynb` in your browser.
3.run each cell by shift+enter.

-> What the Notebook Does
1. Reads the CSV file (skipping metadata rows).
2. Extracts columns for **Country Name** and **2024 population**.
3. Converts and cleans the data.
4. Sorts and displays the **top 10** most populous countries.
5. Plots a bar chart with readable labels and gridlines.

-> Notebook Highlights
* Clear markdown explanations between cells.
* Beautiful bar chart using `plt.bar(...)` with `skyblue` color.

 ->Requirements
pandas
matplotlib
jupyter


