# CODA 2.0: Analyzing India's Education Landscape through NIRF 2024 Seat Matrix

![Education Analysis Banner](https://img.shields.io/badge/Project-CODA%202.0-blueviolet?style=for-the-badge&logo=jupyter)  
![Python](https://img.shields.io/badge/Python-3.12-brightgreen?style=flat&logo=python)  
![Libraries](https://img.shields.io/badge/Libraries-Pandas%20%7C%20NumPy%20%7C%20Matplotlib%20%7C%20Seaborn-orange?style=flat)  
![License](https://img.shields.io/badge/License-MIT-green?style=flat)  

---

## 🚀 Project Overview

**CODA 2.0** is a data-driven exploration aimed at uncovering disparities in India's higher education system. By analyzing the **NIRF 2024 Seat Matrix** data, this project identifies states with potentially weaker education infrastructure and opportunities. The core insight? Higher mean closing ranks in college admissions often signal lower competition, which could indicate limited access to quality education, fewer prestigious institutions, or underdeveloped opportunities.

This analysis empowers policymakers, educators, and students to spotlight regions needing urgent improvements for equitable growth.

**Key Question:** Which states have the weakest education systems based on admission trends?

---

## 🎯 Objectives

- **Identify Weak Spots:** Pinpoint states like Sikkim, Manipur, and Mizoram with higher mean closing ranks, suggesting lower education quality or desirability.
- **Highlight Strengths:** Recognize competitive states such as Karnataka, Maharashtra, and Tamil Nadu with lower closing ranks, indicating robust education ecosystems.
- **Drive Action:** Provide data-backed recommendations for governments to upgrade policies, infrastructure, and opportunities in underperforming states.

---

## 📊 Data Sources

- **Primary Dataset:** `2024_Seat_Matrix.csv` – Contains details on institute names, programs, seat pools, reservations (OPEN, SC, ST, etc.), and total seats across India.
- **Additional Context:** References to JoSAA Round 5 data for closing ranks (integrated in the analysis).
- **Scope:** All India seats from IITs, NITs, IIITs, and other central universities.

**Note:** Data is sourced from official NIRF/JoSAA releases. Ensure you have the CSV file in your working directory.

---

## 🛠️ Methodology

1. **Data Loading & Preparation:**
   - Import libraries: Pandas, NumPy, Matplotlib, Seaborn.
   - Load the seat matrix CSV and perform basic EDA (Exploratory Data Analysis) – describe data, check for nulls, and visualize distributions.

2. **Analysis Steps:**
   - Group data by states/institutes.
   - Calculate mean closing ranks (from Round 5 integrations).
   - Visualize trends using bar plots, heatmaps, and scatter plots for seat distribution vs. ranks.
   - Compare categories: Gender-neutral vs. Female-only seats, reservation impacts.

3. **Key Metrics:**
   - **Mean Closing Rank:** Higher values indicate easier admissions (potentially weaker demand/quality).
   - **Seat Availability:** Total seats per state/program.
   - **Reservation Breakdown:** OPEN, EWS, SC, ST, OBC distributions.

4. **Tools Used:**
   - Python 3.12 in Jupyter Notebook.
   - Visualizations: Seaborn for heatmaps, Matplotlib for plots.

---

## 🔍 Key Findings

- **Underperforming States:**  
  Sikkim, Manipur, and Mizoram show **higher mean closing ranks**, pointing to:  
  - Limited high-quality institutions.  
  - Lower student competition.  
  - Potential gaps in education infrastructure and opportunities.

- **Top-Performing States:**  
  Karnataka, Maharashtra, and Tamil Nadu exhibit **lower closing ranks**, reflecting:  
  - Strong education systems with prestigious colleges.  
  - High competition and better opportunities.

- **Visual Insights:**  
  (Refer to the notebook for plots)  
  - Bar chart: Mean Closing Ranks by State.  
  - Pie chart: Seat Distribution Across Categories.  

**Conclusion:** States with higher ranks need targeted investments in education policies, faculty, and infrastructure to foster growth and competition. This could bridge the gap and elevate national education standards!

---

## 📈 How to Run the Project

### Prerequisites
- Python 3.12+  
- Install dependencies:  
  ```
  pip install pandas numpy matplotlib seaborn
  ```

### Setup & Execution
1. Clone the repo:  
   ```
   git clone https://github.com/yourusername/coda-2.0.git
   cd coda-2.0
   ```

2. Place the dataset:  
   - Download `2024_Seat_Matrix.csv` and add it to the project root (or update the file path in the notebook).

3. Run the Notebook:  
   - Open `CODA 2.0.ipynb` in Jupyter:  
     ```
     jupyter notebook CODA 2.0.ipynb
     ```
   - Execute cells sequentially for data loading, analysis, and visualizations.

4. Explore:  
   - Modify queries or add new visualizations to dive deeper!

---

## 📝 Contributing

Contributions are welcome! If you have ideas for advanced analytics (e.g., ML predictions on future ranks) or additional datasets:  
- Fork the repo.  
- Create a feature branch.  
- Submit a Pull Request.  

Please follow standard coding practices and add comments to your code.

---

## 👥 Credits

- **Author:** Kanhaiya Mehta  
- **Inspiration:** NIRF/JoSAA data for promoting educational equity in India.  
- **Tools:** Built with love using Jupyter, Pandas, and friends ❤️.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Thank You for Exploring CODA 2.0!**  
If this project sparks ideas or helps in your research, star the repo ⭐ or share your thoughts. Let's build a better education system together! 🚀