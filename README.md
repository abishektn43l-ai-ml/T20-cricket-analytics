# 🏏 T20 Cricket Analytics
### Data-Driven Cricket Analysis & Best XI Selection

## 📌 Project Overview

T20 Cricket Analytics is an end-to-end sports data analytics project focused on analysing T20 World Cup cricket data.

The project uses data extraction, data preprocessing, Python and Microsoft Power BI to transform raw cricket data into meaningful insights about team performance, batting statistics, bowling performance and player selection.

The primary objective is to analyse player performances and identify the best possible playing XI based on statistical performance.

## 🎯 Project Objectives

- Extract and explore T20 cricket match data.
- Process raw JSON data into structured datasets.
- Clean and transform data using Python and Pandas.
- Analyse batting and bowling performances.
- Identify key performance indicators for players.
- Develop an interactive Power BI dashboard.
- Select the Best Playing XI based on performance metrics.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data processing and analysis |
| Jupyter Notebook | Interactive development |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| JavaScript | Web scraping scripts |
| JSON | Raw data storage |
| CSV | Processed data storage |
| Microsoft Power BI | Dashboard development |
| DAX | Measures and calculated columns |
| Git & GitHub | Version control |

## 📂 Project Structure

```text
T20-Cricket-Analytics/
│
├── data/
│   ├── raw/
│   │   └── json/
│   │
│   └── processed/
│       └── csv/
│
├── notebooks/
│   └── t20_data_preprocessing.ipynb
│
├── web_scraping/
│   ├── t20_wc_batting_summary.js
│   ├── t20_wc_bowling_summary.js
│   ├── t20_wc_match_results.js
│   └── t20_wc_player_info.js
│
├── power_bi/
│   ├── T20-Cricket-Analytics.pbix
│   └── DAX-Measures-and-Calculated-Columns.xlsx
│
├── screenshots/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## ⚙️ Project Workflow

### 1. Data Extraction

- Collect T20 World Cup cricket data.
- Extract match results, batting summaries, bowling summaries and player information.
- Store the raw datasets in JSON format.

### 2. Data Preprocessing

Use Python and Pandas through Jupyter Notebook to:

- Load raw JSON files.
- Explore the available data.
- Handle missing and inconsistent values.
- Transform raw data into structured datasets.
- Prepare datasets for further analysis.

### 3. Data Transformation

Convert the processed datasets into CSV files for analytical use.

### 4. Power BI Dashboard

Import the processed datasets into Power BI.

Use Power Query, data modelling and DAX calculations to develop interactive cricket performance dashboards.

### 5. Best XI Selection

Analyse player performance using relevant batting and bowling statistics to identify a balanced and competitive playing XI.

## 📊 Key Analytical Areas

- Batting performance analysis
- Bowling performance analysis
- Player consistency
- Strike rate and batting averages
- Bowling economy and wickets
- Match and team performance
- Best Playing XI selection

## 💻 Installation and Setup

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Microsoft Power BI Desktop
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/T20-Cricket-Analytics.git
```

### Step 2: Navigate to the Project

```bash
cd T20-Cricket-Analytics
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

### Step 4: Activate the Environment

Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### Step 5: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 6: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the preprocessing notebook inside the `notebooks` folder.

### Step 7: Open the Power BI Dashboard

Open the `.pbix` file inside the `power_bi` folder using Microsoft Power BI Desktop.

## 📈 Dashboard

Power BI dashboards provide interactive insights into T20 cricket player and team performance.

Project screenshots will be added to the `screenshots/` directory.

## 🔍 Key Findings

Key analytical findings and player performance insights will be documented here after validating the completed analysis.

## 📚 Learning Outcomes

Through this project, I aim to develop practical experience in:

- Working with structured and semi-structured datasets.
- Data extraction and preprocessing.
- Python-based data analysis.
- Data transformation and modelling.
- DAX calculations.
- Interactive dashboard development.
- End-to-end analytics project development.

## 🙏 Acknowledgements

This project is based on learning resources and reference materials from Codebasics.

Credit is given to the original creators of the project materials and datasets. This repository is maintained as a learning and portfolio implementation.

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/abishektn43l-ai-ml

---

⭐ If you find this project interesting, feel free to explore the repository and share your feedback.
