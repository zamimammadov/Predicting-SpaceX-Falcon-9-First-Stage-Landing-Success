# 🚀 SpaceX Falcon 9 First Stage Landing Prediction  
*Applied Data Science Capstone – IBM / Coursera*  

## 📌 Project Overview  
SpaceX has revolutionized the aerospace industry by successfully landing reusable rocket boosters, dramatically reducing the cost of space travel.  
This project aims to **predict the landing success of Falcon 9 first stages** using historical launch data. The ability to accurately forecast landings can provide valuable insights for stakeholders, engineers, and investors when estimating launch costs.  

---

## 🎯 Objectives  
- Collect SpaceX launch data via **SpaceX REST API** and **web scraping** (Wikipedia).  
- Perform **data wrangling** and cleaning for structured analysis.  
- Conduct **Exploratory Data Analysis (EDA)** using **SQL**, **Pandas**, **Matplotlib**, **Seaborn**.  
- Build **interactive visualizations** with **Folium** (geospatial) and **Plotly Dash** (dashboard).  
- Develop and evaluate **machine learning models** (Logistic Regression, Decision Tree, SVM, KNN).  
- Identify the most accurate model for predicting Falcon 9 first-stage landing outcomes.  

---

## 📂 Repository Structure:
    
    ```bash
    .
    ├── 📁 data/                # Raw and processed datasets
    ├── 📁 notebooks/           # Jupyter notebooks (step-by-step workflow)
    │   ├── 01_data_wrangling.ipynb
    │   ├── 02_eda_sql.ipynb
    │   ├── 03_eda_visual.ipynb
    │   ├── 04_interactive_maps.ipynb
    │   ├── 05_machine_learning.ipynb
    │   └── 06_dashboard_app.ipynb
    ├── 📁 app/                 # Plotly Dash dashboard files
    ├── 📁 reports/             # Final report & presentation
    ├── 📄 requirements.txt     # Project dependencies
    └── 📄 README.md            # Project documentation

---

## 🛠️ Tools & Technologies  
- **Languages:** Python, SQL  
- **Libraries:** Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, Folium, Plotly, Dash, BeautifulSoup, Requests  
- **Platforms:** Jupyter Notebook, IBM Watson Studio, GitHub  
- **Deployment:** Plotly Dash (local / cloud)  

---

## 🔎 Exploratory Data Analysis  
- Distribution of successful vs. failed landings  
- Correlation of payload mass, orbit type, and flight number with landing outcome  
- Geospatial mapping of launch sites using **Folium**  
- Interactive visualizations with **Plotly** for deeper insights  

---

## 🤖 Machine Learning Models  
The following models were trained and compared:  
- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  

**Evaluation Metrics:** Accuracy, F1-Score, Cross-Validation  

📈 **Best Model:** Decision Tree (with tuned hyperparameters), achieving ~XX% accuracy. *(Update XX% with your actual score)*  

---

## 📊 Dashboard  
An interactive **Plotly Dash App** was created to allow users to:  
- Filter launches by site, payload, and orbit  
- Visualize success rates over time  
- Explore the relationship between payload mass and landing success  

*(Insert screenshot or gif of your dashboard here)*  

---

## 📑 Results & Insights  
- Payload mass and orbit type are significant predictors of landing success.  
- Launch site location has a strong correlation with landing probability.  
- With the selected ML model, we can predict landings with an accuracy of **XX%**.  

---

## 📌 Conclusion  
This project demonstrates how **data science and machine learning** can be applied to real-world aerospace problems. Predictive modeling provides valuable foresight into mission success rates and potential cost reductions for space travel.  

---

## 🚀 How to Run the Project  

1. Clone this repository:  
   
   ```bash
   git clone https://github.com/yourusername/ibm-spacex-capstone.git
   cd ibm-spacex-capstone


2. Install dependencies:
    
    ```bash
    pip install -r requirements.txt


3. Run Jupyter notebooks step by step.
     
4. Launch the dashboard locally:
    
    ```bash
    python app/app.py

📚 References

SpaceX REST API

Wikipedia Falcon 9 Launch Data

IBM Data Science Professional Certificate (Coursera)


---
