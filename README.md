# Spatio-Temporal Analysis of Failed Orders

## Overview
This project performs **advanced analytics and visualization** on order and offer datasets to analyze failed delivery orders.  
Using geospatial and temporal methods, it uncovers operational inefficiencies, customer behavior, and supply-demand gaps.

---

## Key Objectives
- Identify **spatial clusters** (hexagonal grids) with high order failure rates using H3.
- Analyze **temporal trends** to detect peak failure hours.
- Perform **driver supply-demand gap analysis** for optimizing driver allocation.
- Provide actionable **business insights** to improve operations.

---

## Datasets
1. **Orders Dataset (`data_orders.csv`)**
   - Includes order ID, timestamps, coordinates, and failure flags.
2. **Offers Dataset (`data_offers.csv`)**
   - Includes driver assignment details, offers made, and acceptance/rejection flags.

---

## Tech Stack
- **Languages**: Python (Pandas, NumPy)
- **Visualization**: Matplotlib, Folium, Branca
- **Geospatial Analysis**: H3
- **Environment**: Jupyter Notebook

---

## How to Run the Project
1. Clone the repository or download the notebook.
2. Install dependencies:
   ```bash
   pip install pandas numpy folium h3 branca matplotlib
   ```
3. Place `data_orders.csv` and `data_offers.csv` in the working directory.
4. Open the notebook and run cells sequentially:
   ```bash
   jupyter notebook Spatio_Temporal_Analysis_Of_Failed_Orders.ipynb
   ```

---

## Business Value
- Identify **failure hotspots** for targeted interventions.
- Improve **driver allocation** and **incentive strategies**.
- Enhance **customer satisfaction** by reducing order cancellations and delays.

---

## Author
kanavchopra2002@gmail.com

---

## Support
If you found this project helpful, consider starring the repository!

## Support
If you found this project helpful, consider starring the repository!
