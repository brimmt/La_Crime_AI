📊 LA Crime AI Project

This project focuses on exploring and analyzing real-world Los Angeles Crime data using Python, with an emphasis on data wrangling, visualization, and AI-driven anomaly detection. The goal was to gain actionable insights while applying both foundational and advanced data analysis skills.

🧠 This project was inspired by a Udemy course focused on data cleaning and visualization in Python. I followed the structure to learn best practices—then built on it by integrating AI techniques like Isolation Forest for anomaly detection to make the project my own.

🚀 Project Highlights
🔹 Data Cleaning

Handled missing values using both manual filtering and SimpleImputer.

Removed unnecessary columns for clearer analysis.

Converted date columns to proper datetime format.

🔹 Data Exploration & Wrangling

Analyzed victim demographics (e.g. age distributions).

Explored crime patterns over time (by year, month, hour).

Investigated reporting delays and top crime types.

Grouped and visualized data across multiple dimensions like time, area, and crime type.

🔹 Visualizations

Created multiple plots using Matplotlib to visualize crime trends:

Crimes over time

Victim age distribution

Top 20 crimes by daily average

Hourly crime breakdowns

Multi-chart dashboard using plt.subplots()

📸 (You can find a screenshot of the visual dashboard in this repo)

🔹 AI Component – Anomaly Detection

Applied Isolation Forest (scikit-learn) to detect unusual or outlier cases in the dataset based on numerical features.

Labeled and visualized anomalous entries vs. normal ones.

🛠️ Tools Used
Python

Pandas

Matplotlib

Scikit-learn (Isolation Forest, SimpleImputer)

Jupyter Notebook

📁 File Contents
LA Crime AI.ipynb: Main notebook containing code, markdowns, insights, and visualizations.

la_crime_visuals.png: Dashboard screenshot containing combined graphs.

💡 What I Learned
End-to-end data analysis: from cleaning to visualization.

Real-world data can be messy — careful wrangling and filtering are key.

Applied AI concepts (Isolation Forest) in a meaningful, practical context.

Importance of documenting work for clarity and sharing.

How to build on a guided project and make it your own with creative extensions.

🧠 Future Improvements
Add more external data (e.g. weather, population) for deeper correlation.

Use Seaborn or Plotly for interactive visualizations.

Deploy as a lightweight web app with Streamlit or Flask.
