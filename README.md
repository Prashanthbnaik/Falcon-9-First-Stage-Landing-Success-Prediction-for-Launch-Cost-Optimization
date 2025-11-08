# Falcon 9 First Stage Landing Success Prediction for Launch Cost Optimization

## Project Overview
Space launch costs are heavily influenced by whether the first stage of a rocket can be recovered and reused. SpaceX advertises a Falcon 9 launch at around **USD 62 million**, while other providers charge upwards of **USD 165 million**.  
Much of this cost advantage is attributed to the reusability of the Falcon 9 first stage.

This project develops a **machine learning model** to predict whether the Falcon 9 first stage will **land successfully**.  
By accurately predicting landing outcomes, this model enables better **launch cost estimation** and supports **competitive bidding** for companies competing with SpaceX.

---

## Learning Objectives
- Load and manipulate real-world launch data using **Python** and **Pandas**.  
- Convert **JSON** and **CSV** files into structured DataFrames for analysis.  
- Perform **exploratory data analysis (EDA)** to uncover insights and relationships.  
- Build **machine learning classification models** to predict landing success.  
- Create a **shareable Jupyter Notebook** and document the workflow via **GitHub**.

---

## Business Value
1. **Cost Predictability** – Predicting the likelihood of first-stage recovery allows better estimation of total mission costs.  
2. **Competitive Bidding** – Enables non-SpaceX providers to quantify recovery success risk when preparing bids.  
3. **Operational Insights** – Helps identify factors influencing landing success, guiding engineering and operational decisions.

---

## Data Pipeline and Methodology
1. **Data Acquisition** – Launch records retrieved via the **SpaceX REST API** and **Wikipedia scraping**.  
2. **Data Wrangling** – Cleaning, transformation, and feature engineering performed on combined datasets.  
3. **Exploratory Analysis** – Statistical and visual analyses using **Pandas**, **Matplotlib**, and **Seaborn**.  
4. **Model Development** – Classification models such as **Logistic Regression**, **Random Forest**, and **XGBoost**.  
5. **Model Evaluation** – Evaluated using metrics like **accuracy**, **precision**, **recall**, **F1-score**, and **ROC-AUC**.  
6. **Visualization & Reporting** – Interactive charts with **Plotly**, maps using **Folium**, and final summary in PDF.

---

## Repository Structure
- 1. Space-X Data Collection API.ipynb
- 2. Space-X Web Scraping Falcon9 & Falcon Heavy.ipynb
- 3. Space-X Data Wrangling.ipynb
- 4. Space-X EDA Using SQL.ipynb
- 5. Space-X Data Visualization.ipynb
- 6. Launch Sites Analysis with Folium.ipynb
- 7. Plotly Dash Interactive Dashboard.ipynb
- 8. Machine Learning Prediction Model.ipynb
- 9. Falcon 9 First Stage Landing Success Prediction for Launch Cost Optimization Report 
- dataset_part_2.csv
- README.md


---

## Tools and Technologies
- **Programming Language:** Python  
- **Data Processing:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn, Plotly, Folium  
- **Machine Learning:** Scikit-learn, XGBoost  
- **Database / Querying:** SQL, SQLite  
- **Environment:** Jupyter Notebook  
- **Version Control:** Git & GitHub  

---

## Key Findings and Insights
- **Launch site** and **booster version** significantly influence landing success probability.  
- **Payload mass** and **orbit type** have measurable effects on landing outcomes.  
- The **best-performing model** achieved a **ROC-AUC score of ~0.89**, showing strong predictive capability.  
- The model enables organizations to estimate landing success probability before a launch, supporting cost-optimized planning and decision-making.

---

## Instructions to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/Prashanthbnaik/Falcon-9-First-Stage-Landing-Success-Prediction-for-Launch-Cost-Optimization.git
   cd Falcon-9-First-Stage-Landing-Success-Prediction-for-Launch-Cost-Optimization



