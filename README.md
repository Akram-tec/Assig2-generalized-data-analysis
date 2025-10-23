# Assig2-generalized-data-analysis
# 🌿 Lab 7 – Generalizing Your Data Analysis Program

### 🎯 Goal
Write a *general, reusable Python program* that can read, analyze, and plot **any small real-world dataset** you find online — without hard-coding column names or values.

---

## 🧭 Step 1 – Choose Your Dataset
Select a **small dataset (10–50 rows)** from one of these sources (or any similar one):

| Theme | Reliable Source | Example Variable | Suggested Plot |
|-------|------------------|------------------|----------------|
| 🌧️ Rainfall | [World Bank Climate Knowledge Portal](https://climateknowledgeportal.worldbank.org/) | Monthly rainfall for one city | Line plot |
| 🌡️ Temperature | [Time and Date – Historic Weather](https://www.timeanddate.com/weather/) | Daily/monthly temperatures | Line plot |
| 🌾 Vegetation (NDVI) | [Kaggle NDVI Datasets](https://www.kaggle.com/search?q=ndvi+dataset) | NDVI values | Bar chart |
| 💧 Water Quality | [Kaggle Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability) *(small subset)* | pH / hardness / solids | Histogram |
| 🔋 Energy or Emissions | [Our World in Data](https://ourworldindata.org/) | Electricity use / CO₂ emissions | Line or bar chart |
| 💡 Environmental Indicators | [World Bank Data (WDI)](https://data.worldbank.org/) | Any environmental indicator | Bar or line chart |

💡 *Tip:* 10–30 rows are enough. You should be able to view all values on one screen.

---

## 🧩 Step 2 – Write Your Program (`analysis.py`)
Create a Python script that:
- Reads `data.csv`
- Automatically detects numeric columns  
- Calculates **mean, min, max, std**
- Creates and saves a plot as `output_plot.png`
- Prints a short summary to the terminal  

⚙️ **Your goal:** Make the code *general* — it should work for any dataset, not just one type.

---

## 📂 Step 3 – Submit on GitHub Classroom
Upload these files to your repository:
1. `data.csv` – your chosen dataset  
2. `analysis.py` – your Python program  
3. `output_plot.png` – your generated plot  
4. `README.md` – describe what dataset you used and what your program does  

---

## 🧾 Marking Rubric (10 Marks)

| Component | Marks | Description |
|------------|-------|-------------|
| Real dataset (online or created) | 2 | Clean and relevant |
| Code generalization | 4 | Works for different datasets without manual edits |
| Output plot | 2 | Properly labeled and meaningful |
| README explanation | 2 | Concise and clear summary |

---

### ✍️ Author
This assignment is part of **Fundamentals of Programming – II (FOP-II)** at IESE, NUST.
