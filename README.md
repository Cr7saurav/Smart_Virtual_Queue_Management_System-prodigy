# traffic-accident-analysis-prodigy
# Traffic Accident Analysis

## 🚧 Project Overview
This project analyzes traffic accident data to identify patterns and contributing factors related to **road conditions**, **weather**, and **time of day**, and to visualize accident **hotspots** on maps. The analysis helps traffic planners, city authorities, and researchers prioritize interventions and understand high-risk situations.

## 🔎 Objectives
- Clean and preprocess accident datasets (CSV, GeoJSON, etc.).
- Explore relationships between accident frequency/severity and features:
  - Road surface and condition
  - Weather conditions (rain, fog, snow)
  - Time of day, day of week, season
  - Speed limits, lighting, road type
- Identify spatial hotspots (high accident density areas).
- Visualize results (heatmaps, choropleth, scattermaps, time series).
- Summarize actionable insights and suggest mitigation ideas.

## 📂 Dataset (example)
Place datasets in `data/raw/`. Example sources:
- Local / government open data portals (city traffic datasets)
- US NHTSA Crash Data, UK STATS19, India’s open data portals
- CSV columns expected (at minimum):
  - `latitude`, `longitude` (or geometry)
  - `date_time` (timestamp)
  - `severity` or `fatal` flag
  - `weather`, `road_surface`, `light_conditions`, `speed_limit`, `road_type
