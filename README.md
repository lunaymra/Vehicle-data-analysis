## 📊 Visualizations
## ✅ Key Insights
## ⚙️ Installation
## 📌 Usage
## 📝 Suggestions for Improvement
## 👤 Author
# Vehicle Data Analysis

This project explores a dataset of vehicles using **Python** and **data visualization** (with pandas, seaborn, and matplotlib).
The goal was to practice data cleaning, analysis, and visualization in a way that’s simple and easy to follow.

---

## 📊 Visualizations

### 1. Vehicle Age Distribution

* **Plot:** Boxplot of vehicle ages (`2025 - Vehicle Year`)
* **Insight:** Most vehicles are fairly new (around 5 years old), but there are some older outliers.

---

### 2. Wheelchair Accessibility

* **Plot:** Pie chart of wheelchair-accessible vs non-accessible vehicles
* **Insight:** The majority (92.5%) are **not accessible**. Only a small share is marked as **WAV** or **PILOT**.

---

### 3. Types of Vehicles

* **Plot:** Bar chart showing distribution of vehicle types (Non-Hybrid, HYB, BEV, WAV, etc.)
* **Insight:** **Non-Hybrid vehicles dominate** the dataset. Hybrid (HYB), Battery Electric (BEV), and WAV vehicles appear less often.

---

### 4. Vehicle Age vs WAV

* **Plot:** Boxplot comparing ages of WAV vs Non-WAV vehicles
* **Insight:** Both groups have a similar age spread, with a few older outliers in each category. No major difference in average age.

---

### 5. Vehicles by Top 5 Companies

* **Plot:** Bar chart of vehicle counts for the top 5 companies
* **Insight:** **Uber USA, LLC** has an overwhelming lead in vehicle count. Other companies (Spacelinks, Tri-City, etc.) have much smaller fleets.

---

### 6. Website Presence Across Companies

* **Plot:** Pie chart showing website presence among top companies
* **Insight:** Only **2.5%** of companies have a website. The majority don’t maintain one.

---

### 7. Vehicle Expiration Trends

* **Plot:** Bar chart of vehicle registration expiration years
* **Insight:** The peak expiration year is **2026**, followed by **2027** and **2025**. This indicates when a large chunk of vehicles will need renewals.

---

## ✅ Conclusion

From this analysis, we can see:

* Most vehicles are relatively **new**.
* **Accessibility is limited** → very few wheelchair-accessible vehicles exist.
* The dataset is heavily dominated by **non-hybrids** and **Uber USA, LLC**.
* Many companies **don’t have websites**, showing a lack of online presence.
* Registration expirations **cluster around 2025–2027**, which could be important for planning fleet renewals.

Overall, this project was a great practice exercise in **data cleaning, visualization, and interpretation**.

📝 Notes & Suggestions

If you’d like to improve this project in the future, here are some ideas:
Add more preprocessing to handle outliers in vehicle ages.
Explore time-series analysis on expiration dates.
Compare fuel types vs vehicle ages to see if newer vehicles are leaning more electric.
Add interactive charts (using Plotly or Dash) for better exploration.
Clean up column naming and standardize labels (e.g., WAV, HYB, BEV).
Feel free to fork this repo and suggest improvements! 🚀

👤 Author
Bushra Fatima~~
