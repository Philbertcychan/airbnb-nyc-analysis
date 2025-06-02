# 🏙 NYC Airbnb: Price & Location Analysis

This project explores Airbnb listings in New York City, focusing on how prices vary across boroughs, neighborhoods, and room types. It includes an interactive Tableau dashboard that supports data-driven insights for hosts, investors, and analysts.

## 📊 Dashboard

👉 [View the interactive Tableau dashboard](https://public.tableau.com/app/profile/philbert.chan/viz/NYCAirbnbAnalysisRoomTypePricingInsights/PriceLocation)

<img src="visuals/dashboard-screenshot.png" alt="Airbnb Dashboard" width="800"/>

## 🔍 Key Insights
- **Manhattan listings** are significantly more expensive and are mostly entire homes/apartments.
- **Private rooms** dominate in Queens and Brooklyn, often at lower price points.
- **The Bronx and Staten Island** offer lower average prices but have fewer listings.
- **Price hotspots** cluster in central Manhattan and parts of Brooklyn near Manhattan.

## 🧰 Tools Used
- **Tableau Public** – for data visualization and dashboard design
- **Pandas + Jupyter (optional)** – for preliminary data exploration
- **NYC Airbnb Open Data (2019)** – from [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)

## 📁 Project Structure
<pre> airbnb-nyc-analysis/ 
  ├── data/ # Raw dataset (e.g., AB_NYC_2019.csv) 
  ├── notebooks/ # (Optional) Jupyter notebooks for EDA or cleaning 
  ├── visuals/ # Tableau screenshots or exports 
  └── README.md # Project overview and documentation </pre>

## 🚀 Future Improvements
- Add time-series analysis if multi-year data is available
- Build a Streamlit app for price prediction or filtering by user input
- Extend to other cities for comparative analysis
