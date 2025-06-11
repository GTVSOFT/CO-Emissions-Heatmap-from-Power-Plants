# CO₂ Emissions Heatmap from Power Plants

This project visualizes carbon dioxide (CO₂) emissions from power plants using an interactive heatmap. By mapping emissions intensity across geographic locations, it supports better monitoring, policy-making, and environmental impact analysis.

---

## 📌 Objective

- Visualize geolocated CO₂ emissions from power plants.
- Identify hotspots and clusters of high emission intensity.
- Enhance climate-related decision-making using spatial data analytics.

---

## 🧠 Methodology

1. **Input Data**: Power plant names, coordinates (latitude/longitude), and CO₂ emissions.
2. **Heatmap Generation**: Normalize emission data for intensity scaling.
3. **Visualization**: Use Folium with Leaflet to generate an interactive HTML map.

---

## 📁 Project Structure

```
CO2-Emissions-Heatmap/
│
├── data/
│   └── power_plants.xlsx            # Emissions dataset
├── figures/
│   └── co2_emissions_heatmap.html  # Output HTML map
├── scripts/
│   └── co2_emissions_heatmap.py    # Python script to generate heatmap
├── requirements.txt                # Project dependencies
└── README.md                       # Project documentation
```

---

## 🚀 How to Run

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Ensure your dataset is in `data/power_plants.xlsx`**

3. **Run the script**
   ```bash
   python scripts/co2_emissions_heatmap.py
   ```

4. **View the map**
   - Open `figures/co2_emissions_heatmap.html` in your browser.

---

## 🔧 Technologies Used

- Python
- Pandas
- Folium
- Leaflet.js (via Folium)

---

## 🧠 Future Enhancements

- Add emissions per capita and energy source type.
- Export map to PNG using `selenium` or `mapshot`.
- Integrate Streamlit or Dash dashboard for dynamic queries.

---

## 👩‍💻 Author

**Ebiere**  
