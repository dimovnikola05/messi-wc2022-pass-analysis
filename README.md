# messi-wc2022-pass-analysis
Python spatial analysis and pass visualization for Lionel Messi in the 2022 World Cup Final using StatsBomb open data.
# ⚽ Lionel Messi Spatial Pass Analysis – World Cup Final 2022

## 📌 Project Overview
This project presents a spatial visual analysis of Lionel Messi's 49 successful passes during the 2022 FIFA World Cup Final (Argentina vs France). 
The analysis is built using Python, focusing on event-data filtering and geospatial visualization.

## 📊 Pass Map Visualization
![Messi Pass Map](messi_passes_final2022.png)

## 🔍 Key Data Insights
* **Primary Zone of Influence:** The majority of progressive passes penetrating the final third originated from the **Right Half-Space**.
* **Positional Drop:** Data reveals a strong trend of Messi dropping deep into the central third to bypass high-pressing structures and dictate build-up play.

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3
* **Data Provider:** StatsBomb Open Data (`statsbombpy`)
* **Data Manipulation:** `pandas`
* **Visualization:** `mplsoccer`, `matplotlib`

## 🚀 How to Run
1. Clone this repository.
2. Install dependencies: `pip install statsbombpy mplsoccer pandas matplotlib`
3. Open `messi_wc2022_pass_map.ipynb` in Jupyter Notebook or Google Colab and execute cells.
