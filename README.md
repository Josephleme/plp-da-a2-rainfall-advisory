# Rainfall Advisory Analysis

This project cleans monthly weather station rainfall data across five Kenyan counties and uses NumPy to identify optimal planting windows for SMS farmer advisories.

## How to Run

1. Install the required library:
   ```bash
   pip install -r requirements.txt
   ```
2. Open `rainfall_analysis.ipynb` in Jupyter Notebook, VS Code, or Google Colab.
3. Run all cells from top to bottom to generate the analysis outputs and `rainfall_summary.csv`.

## Planting Advisory

* Farmers in Nairobi, Nakuru, Kisumu, and Mombasa should align planting with their peak April–May rainfall window, while Machakos farmers should target the November–December short rains.
* Kisumu offers year-round moisture with 1,371 mm of annual rain and zero dry months, whereas Machakos experiences seven dry months below 50 mm and requires drought-resilient seed varieties.
* Note that Machakos readings for April and September were missing in the raw station logs and were imputed using the station's valid monthly average (68 mm), so local field verification is advised before April planting.
