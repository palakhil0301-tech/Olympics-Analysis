# 🏅 Olympics Data Analysis Dashboard

An interactive **Olympics Data Analysis Dashboard** built using **Python, Pandas, Streamlit, Plotly, Matplotlib, and Seaborn**.

The application analyzes historical **Summer Olympics data** and provides interactive insights into medal tallies, participating nations, events, athletes, sports, and athlete demographics.

## 🚀 Live Application

🔗 **[Open the Olympics Analysis Dashboard]( https://olympics-analysis-cen3ptnltzofzcdy7segph.streamlit.app)**

---

## 📌 Project Overview

This project transforms historical Olympics data into an interactive analytical dashboard.

Users can explore:

* 🥇 Medal tallies by country and Olympic year
* 🌍 Participation of nations over time
* 🏟️ Number of events and sports across Olympic editions
* 🏃 Athlete participation trends
* 🏆 Most successful athletes
* 🌎 Country-wise medal performance
* 🏅 Sports in which a country has won medals
* 👤 Athlete age distributions
* 📏 Height vs. weight relationships
* 👨‍🦱👩‍🦰 Male vs. female participation over time

---

## 🚀 Features

### 🥇 Medal Tally

Users can filter the medal tally by:

* Olympic Year
* Country

The dashboard displays:

* Gold medals
* Silver medals
* Bronze medals
* Total medals

It also supports an **Overall** option for viewing cumulative performance.

### 📊 Overall Analysis

Provides:

* Number of Olympic editions
* Host cities
* Sports
* Events
* Participating nations
* Athletes
* Participating nations over time
* Events over time
* Athletes over time
* Events-by-sport heatmap
* Most successful athletes

### 🌎 Country-wise Analysis

Select a country to explore:

* Medal tally over the years
* Sports in which the country won medals
* Top 10 athletes from the country

### 👤 Athlete-wise Analysis

Includes:

* Athlete age distribution
* Gold medalist age distribution by sport
* Height vs. weight analysis
* Male vs. female participation over time

---

## 🛠️ Tech Stack

| Technology | Purpose                        |
| ---------- | ------------------------------ |
| Python     | Core programming language      |
| Pandas     | Data manipulation and analysis |
| NumPy      | Numerical operations           |
| Streamlit  | Interactive dashboard          |
| Plotly     | Interactive visualizations     |
| Matplotlib | Data visualization             |
| Seaborn    | Statistical visualization      |

---

## 📂 Project Structure

```text
olympics-analysis/
│
├── app.py
├── helper.py
├── preprocessor.py
├── athlete_events.csv
├── noc_regions.csv
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/olympics-analysis.git
cd olympics-analysis

python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
streamlit run app.py
```

For Windows:

```bash
.venv\Scripts\activate
```

---

## 📊 Dataset

The project uses:

* `athlete_events.csv` — athlete-level Olympic data
* `noc_regions.csv` — NOC-to-country/region mapping

The data includes information such as athlete name, age, height, weight, country, year, sport, event, and medal.

---

## 🎯 Skills Demonstrated

* Python
* Pandas
* NumPy
* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Data Aggregation
* GroupBy Operations
* Data Visualization
* Plotly
* Matplotlib
* Seaborn
* Streamlit
* Interactive Dashboard Development
* Data Storytelling

---

## 👨‍💻 Author

**Akhilesh Pal**

Master's in Statistics | Data Analyst | Python | SQL | Power BI | Machine Learning

---

⭐ **If you found this project useful, consider starring the repository!**
