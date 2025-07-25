# NYC-Airbnb-Data-Analysis
Exploratory data analysis and geo-visualization of NYC Airbnb listings to uncover price and location trends.

# 🗽 NYC Airbnb Analysis (2019)

Explore the Airbnb rental landscape in New York City using powerful data analysis and interactive geo-visualizations. This project dives deep into neighborhood trends, price distributions, availability, and host behaviors.

---

## 📂 Dataset

- **Source:** [Kaggle - NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- **File Used:** `AB_NYC_2019.csv`
- **Rows:** 48,895  
- **Columns:** 16

---

## 🔍 Objective

Analyze and visualize Airbnb listings across NYC to uncover:
- Pricing patterns by neighborhood
- Host types and availability trends
- Distribution of property types
- Geo-based insights using maps

---

## 📊 Key Questions Explored

1. **Which neighborhoods are most expensive?**
2. **Where are most listings located?**
3. **How does availability vary across locations?**
4. **What types of room listings are most popular and expensive?**
5. **Which hosts have the highest number of listings?**
6. **Which neighborhoods have the highest average prices?**

---

## 📈 Insights & Answers

| 🔍 Question | ✅ Insight |
|------------|-----------|
| Which neighborhood is most expensive on average? | **Manhattan** has the highest average prices. |
| Which room type dominates the market? | **Entire home/apartment** is the most common and expensive. |
| Most listings are in which neighborhood group? | **Brooklyn** has the highest number of listings, followed by **Manhattan**. |
| How many hosts own 10+ properties? | There are multiple high-volume commercial hosts with **10+ listings**. |
| What’s the typical price range? | Most listings fall under **$200**, with some luxury listings reaching over **$5000**. |
| Where is availability low? | High-cost neighborhoods like **Manhattan** have many properties with limited availability (under 50 days/year). |

---

## 🗺️ Geo Visualization (Interactive Map)

An interactive Folium map shows property locations across NYC.

✅ View: `nyc_airbnb_map.html`  
📍 Each marker represents a listing with price and name info.

You can open this file in any browser to explore:

```bash
nyc_airbnb_map.html
```

🧪 Tools Used

Python
Jupyter Notebook
Pandas, NumPy (data wrangling)
Matplotlib, Seaborn (visualizations)
Folium (geo-visualization)
Scikit-learn (optional clustering)

🧾 How to Run

Step 1: Clone the repo:
```bash
git clone https://github.com/yourusername/nyc-airbnb-analysis.git
```
Step 2: Navigate into the project folder:
```bash
cd nyc-airbnb-analysis
```
Step 3: Create a virtual environment (optional):
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```
Step 4: Install requirements:
```bash
pip install -r requirements.txt
```
Step 5: Launch the notebook:
```bash
jupyter notebook
```

💡 Future Work

Clustering using KMeans to define optimal pricing zones

Time series trend analysis (if date columns available)

Dashboard integration using Streamlit or Tableau

🙌 Acknowledgments

Kaggle Datasets

Airbnb NYC data contributors
