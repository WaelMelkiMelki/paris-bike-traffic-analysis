# Paris Bicycle Traffic Analysis 🚲

## Context
This project analyzes bicycle traffic data in Paris to understand mobility patterns. The goal is to distinguish between utilitarian usage ("Vélotaf" / Commuting) and leisure usage, and to predict traffic volume based on temporal and geographical features.

## 🎯 Objectives
1.  **Data Cleaning & Feature Engineering:** Process raw OpenData from Paris.
2.  **Clustering (K-Means):** Segment counters into profiles (Commuting vs Leisure).
3.  **Mapping:** Visualize the typology of cycling paths in Paris.
4.  **Prediction (Random Forest):** Model the traffic volume ($R^2 = 0.87$).

## 📊 Key Results
*   **95% of traffic is utilitarian:** Only 3 counters out of ~100 show a "Leisure" profile.
*   **Predictability:** Traffic is highly structured by **Location** and **Hour of day**.
*   **Model Performance:** The Random Forest model predicts traffic with an accuracy of **87%**.

## 🛠️ Tech Stack
*   **Python**: Pandas, NumPy
*   **Visualization**: Matplotlib, Seaborn
*   **Machine Learning**: Scikit-learn (K-Means, Random Forest)
*   **Geospatial**: Folium

## 📂 Project Structure
*   `notebooks/`: Contains the Jupyter Notebook with the full analysis.
*   `reports/`: HTML exports and the interactive map (`carte_typologie.html`).

## 🔗 Data Source
Data provided by [OpenData Paris](https://opendata.paris.fr/pages/home/).