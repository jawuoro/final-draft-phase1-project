the following is the Tableau link to lead you to the interactive dashboard :https://public.tableau.com/app/profile/allan.jawuoro/viz/aviationassesmentdashboard/Dashboard1
# Final Draft Phase-1 Project: Aviation Accident Analysis

## Overview  
This project explores aviation accident data to perform Exploratory Data Analysis (EDA) and build an interactive dashboard using Tableau.  
The goal is to gain insights into patterns, risk factors, and trends in aviation accidents over time.

---

## Business Understanding  
**Stakeholders:**  
- Aviation safety regulators and oversight bodies  
- Airlines and aircraft operators  
- Insurance and risk assessment companies  
- Researchers in aviation safety and public policy  

**Key Business Questions:**  
1. What are the major factors (geographic region, aircraft type, weather, etc.) associated with higher accident frequencies or severities?  
2. How have aviation accident trends evolved over time (increases, decreases, seasonal cycles)?  
3. Can we identify patterns or risk hotspots that stakeholders should monitor or mitigate?

---

## Data Understanding and Analysis  

### Source of Data  
- The dataset `AviationData.csv` provides raw records of aviation accidents.  
- An additional processed dataset `df_Accidents_Final.xlsx` is used in analysis and dashboarding.  

### Description of Data  
Key fields/columns include (examples):  
- **Date / Year**: When the accident occurred  
- **Location / Country / Region**: Geographical context  
- **Aircraft Type / Operator**: Who was operating / what aircraft  
- **Cause / Contributing factors**: Possible causes or conditions  
- **Number of Fatalities / Injuries**: Severity measures  
- **Other contextual features**: Weather, phase of flight, etc.  

#### Data Preprocessing & Cleaning  
- Null / missing values were handled via exclusion or imputation as appropriate  
- Data types (dates, numeric) were standardized  
- Categorical variables were encoded/standardized  
- Outliers and extreme values were examined and filtered where necessary  

### Visualizations  
Below are the **three key visualizations** that were generated (same ones used in the slides and notebook):

1. **Trend of aviation accidents over years**  
   ![Accidents over Time](path/to/visualization1.png)  

2. **Accident counts by region or country (map or bar chart)**  
   ![Accidents by Region](path/to/visualization2.png)  

3. **Factor-driven analysis (e.g. accidents by aircraft type vs fatalities)**  
   ![Aircraft Type vs Fatalities](path/to/visualization3.png)  

*Note: Insert the actual images (exported from your notebook/slides) into the repo and reference their paths above.*

---

## Conclusion  

### Summary of Conclusions  
- **Finding 1:** (e.g.) The number of aviation accidents has overall **decreased** over the past decade, though there remain occasional spikes in certain years.  
- **Finding 2:** Certain regions / countries show disproportionately **higher accident rates**, suggesting need for targeted safety improvements.  
- **Finding 3:** Specific aircraft types or operational contexts (e.g. small private aircraft, certain phases of flight) have **higher severity or fatality risk**.  

These insights can inform regulatory focus, airline operational risk strategies, and targeted safety investments.

---

## Additional Details & Resources  
- **Interactive Dashboard:** You can explore the data through this Tableau dashboard:  
  [Aviation Assessment Dashboard](https://public.tableau.com/app/profile/allan.jawuoro/viz/aviationassesmentdashboard/Dashboard1) :contentReference[oaicite:1]{index=1}  
- **Notebook:** `student.ipynb` contains the full data exploration, cleaning, and visualization pipeline.  
- **Datasets:**  
  - `AviationData.csv` – original raw data  
  - `df_Accidents_Final.xlsx` – cleaned / processed data for analysis  

---

## How to Use / Run Locally  

1. Clone this repo  
2. Ensure you have Python environment (e.g. with `pandas`, `matplotlib` / `seaborn` / `plotly`)  
3. Open and run `student.ipynb` to explore steps  
4. Export visualizations (PNG/SVG) and place them in a `figures/` directory  
5. View or publish the Tableau dashboard  

---

## License & Attribution  
You may include a license (e.g. MIT, CC-BY) depending on your preference.  
Also acknowledge the original data source (if it’s from a public agency, etc.).

---

## Contact  
Project by **Allan Jawuoro**  
Feel free to open issues or reach out via GitHub.


