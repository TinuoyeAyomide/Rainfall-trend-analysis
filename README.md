Rainfall Trend and Variability Analysis (Kwara, Nigeria, 1990–2020)

This project explores 30 years of monthly rainfall data (1990–2020) in Kwara State, Nigeria to understand long-term rainfall trends and variability.  
It demonstrates how Python can be used for environmental and climate data analysis, which are skills that are valuable in hydrology, water resources, and climate change research.

---

Objectives
- Analyze monthly and annual rainfall patterns  
- Identify long-term rainfall trends and variability  
- Visualize rainfall data to reveal climate insights  

---

Tools & Libraries
- Python: Pandas, Matplotlib, Seaborn  
- Dataset:BNASA POWER (sampled rainfall data for Kwara State), NiMET
- Visualization: Line plots showing rainfall trends (1990–2020)

---

Example Output
Average annual rainfall in Kwara State (1990–2020):

![Rainfall Trend](visuals/rainfall_trend_plot.png)

How to Run
1. Clone this repository to your local machine:  
   ```
   git clone https://github.com/TinuoyeAyomide/rainfall-trend-analysis.git

2. Install dependencies:  
   ```
   pip install -r requirements.txt

3. Run the Python script:  
   ```
   python scripts/rainfall_analysis.py

---

Data Description
| Column | Description |
|---------|--------------|
| Year | Year of observation |
| Month | Month of observation (1–12) |
| Rainfall (mm) | Monthly rainfall in millimeters |

---

Future Work
- Compare rainfall trends across multiple Nigerian states  
- Integrate temperature and crop yield data for correlation analysis  
- Apply machine learning for rainfall prediction  
- Use GeoPandas or QGIS for spatial visualization and mapping  

---

Author
Ayomide TINUOYE  
- 🌍 GitHub: [TinuoyeAyomide](https://github.com/TinuoyeAyomide)  
- 📧 Email: Tinuoyeayomide@gmail.com  
- 🎓 Field: Water Resources & Environmental Engineering  

---

Acknowledgment
Dataset adapted from publicly available NASA POWER and the Nigerian Meterological Agency rainfall data.
