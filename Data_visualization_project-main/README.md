# 🎬 Movie Industry Analysis Dashboard

## 📊 Project Overview
This project presents an interactive web-based dashboard for exploring the **TMDB 5000 Movie Dataset**. Designed using **Plotly Dash (Python)**, the application provides a comprehensive visualization of the global movie industry. It uncovers deep insights into financial performances across genres, the correlation between budgets and box-office returns, industry output over time, and detailed distribution metrics. 

Our goal is to provide an analytical tool that allows users to quickly understand the dynamics of the movie industry through 11 distinct, interactive visualizations.

## 📁 Dataset Information
*   **Domain:** Project 10: Movie Industry Analysis
*   **Source:** TMDB (The Movie Database) 5000 Movie Dataset
*   **Size:** Approximately 5,000 films
*   **Processed File:** `cleaned_data.csv` (Output of the data preprocessing phase)
*   **Key Metrics Analyzed:** Budget, Box Office Revenue, Popularity, Runtimes, Genres, Production Companies, and Vote Averages (Ratings).

## 👥 Team Roles & Responsibilities
The project was distributed among 5 team members to ensure all aspects of the data pipeline, UI/UX, interactivity, and documentation were covered.

**1. Mohsen: Data Lead & Relationship Analysis**
*   **Core Tasks:** Managed the Data Preprocessing Notebook (`.ipynb`) documenting cleaning/transformation steps and delivered the final `cleaned_data.csv`.
*   **Charts:** Scatter Chart (Budget vs. Box Office) and Bubble Chart (Budget vs. Revenue vs. Popularity).

**2. Mafi: UI/UX & Comparison Analysis (Part 1)**
*   **Core Tasks:** Designed the dashboard layout, header, visual appeal, and managed `Assets/style.css` for custom, responsive styling.
*   **Charts:** Column Chart (Financial performance by genre), Bar Chart (Runtimes by production company), and Stacked Column Chart (Budget vs Profit across genres).

**3. Nouran: Interactivity & Distribution Analysis**
*   **Core Tasks:** Served as the "brain" of the app by implementing interactive elements (dropdowns, sliders) and connecting Dash Callbacks for dynamic updates.
*   **Charts:** Histogram (Movie ratings distribution), Box Chart (Runtime distribution by genre), and Violin Chart (Revenue distribution by language).

**4. Fouly: Documentation & Comparison Analysis (Part 2)** *(This section)*
*   **Core Tasks:** Managed project documentation (`README.md`) and ensured reproducibility via `requirements.txt`.
*   **Charts:** Stacked Bar Chart (Ratings across languages), Clustered Column Chart (Budget vs. Revenue across years), and Clustered Bar Chart (Industry output vs. revenue).

**5. Ashraf: Application Integration & Time-Series Analysis**
*   **Core Tasks:** Built and maintained `app.py`, acting as the "Conductor" to integrate all team members' reusable functions into the final layout.
*   **Charts:** Line Chart (Evolution of movie output over years) and Area Chart (Growth of total industry revenue over time).

## 🚀 Run Instructions
Follow these steps to run the application on a fresh installation safely:

### 1. Prerequisites
Ensure you have **Python 3.8+** installed on your system. 

### 2. Create a Virtual Environment (Recommended)
It is highly recommended to use a virtual environment to avoid dependency conflicts.
**Windows:**
```cmd
python -m venv venv
venv\Scripts\activate
```
**Mac/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
Install all required libraries using the `requirements.txt` file provided by Fouly:
```bash
pip install -r requirements.txt
```

### 4. Run the Application
Start the local Dash server by running the main application script:
```bash
python app.py
```

### 5. View the Dashboard
Once the server is running, open your web browser and navigate to:
```text
http://127.0.0.1:8050/
```

## ✅ Final Checklist Met
*   **Mandatory Charts:** All 11 distinct chart types are outlined to ensure no mark deduction.
*   **Visual Standards:** All charts include clear titles, properly labeled axes, and consistent dark-mode styling (`plotly_dark`).
*   **Academic Integrity:** The code is modularized (`Charts.py` and `app.py`) for clean architecture and easy explanation during the Q&A session.