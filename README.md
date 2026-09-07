# Student Performance Analysis

A data science project focused on performing exploratory data analysis (EDA) to identify and analyze key academic and behavioral factors that impact student performance outcomes.

## 🚀 Overview

This repository contains an end-to-end data analysis pipeline built to uncover insights regarding how student habits (such as study hours, attendance rates, sleep patterns, and parental environment) correlate with final exam scores. 

### Key Deliverables:
*   Performed exploratory data analysis on student academic and behavioral records.
*   Used **Pandas** and **NumPy** for robust data manipulation, filtering, and structural preprocessing.
*   Leveraged **Matplotlib** and **Seaborn** to build clear statistical plots, distributions, and correlation maps.
*   Evaluated relationships between qualitative attributes and final student grades.

## 🛠️ Tech Stack & Dependencies

The project is written entirely in **Python** using standard data science packages:
*   [Python (v3.10+)](https://python.org)
*   [Pandas](https://pydata.org)
*   [NumPy](https://numpy.org)
*   [Matplotlib](https://matplotlib.org)
*   [Seaborn](https://pydata.org)
*   [Jupyter Notebook / Interactive Kernel](https://jupyter.org)

## 📁 Project Structure

```text
├── notebooks/
│   └── analysis.ipynb        # Main Jupyter notebook containing data pipeline & plots
├── data/
│   └── students.csv          # Local dataset file (or generation script)
├── requirements.txt          # Python dependencies log
└── README.md                 # Project documentation
```

## ⚙️ Installation & Local Setup

To run this project locally on your machine from scratch, follow these instructions:

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Student-Performance-Analysis
   ```

2. **Create and activate a virtual environment:**
   *   **Windows:**
       ```bash
       python -m venv venv
       venv\Scripts\activate
       ```
   *   **Mac/Linux:**
       ```bash
       python -m venv venv
       source venv/bin/activate
       ```

3. **Install the dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter ipykernel
   ```

4. **Launch the environment:**
   Open the repository folder in VS Code, open `notebooks/analysis.ipynb`, select your `venv` kernel at the top right, and execute the cells sequentially.

## 📊 Core Insights Captured
*   **Study Trends:** Quantifiable positive correlation identified between total weekly hours studied and upward shifts in metric averages.
*   **Behavioral Intersections:** Visual exploration highlights the statistical impact of secondary qualitative metrics (like high vs. low parental support tiers) on final outcomes.
