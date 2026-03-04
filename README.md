Palworld Data Visualization Dashboard

An interactive data visualization dashboard built using Python, Dash, Plotly, and Pandas to analyze and explore the characteristics of Palworld creatures (Pals).

This project provides multiple interactive charts to understand Pal types, rarity, combat stats, skills, speed attributes, economy, and item drops using data-driven visualizations.

Project Overview

This dashboard analyzes the Palworld dataset and presents insights through interactive graphs. It helps users explore relationships between different attributes of Pals such as:

Type distribution

Rarity levels

Combat statistics

Skill combinations

Speed attributes

Economic value

Item drops

The dashboard allows users to interact with the data through dropdowns, filters, and dynamic visualizations.

Features
1. Pal Distribution and Characteristics

Count of Pals by Type

Count of Pals by Rarity

Average combat stats by type (HP, Melee Attack, Magic Attack, Defense)

Price vs Rarity scatter plot

Distribution of combat stats using histograms and box plots

2. Pal Skills and Work Suitability

Stacked bar chart of skill levels by Pal type

Distribution of different work skill combinations

Skill correlation heatmap

Parallel coordinates plot for comparing multiple skills simultaneously

3. Pal Combat Attributes

3D combat stats visualization

Radar chart comparing combat abilities

Relationship between Attack and Defense

Speed analysis:

Walk Speed

Run Speed

Ride Sprint Speed

4. Pal Value and Economy

Price distribution by rarity using violin plots

Analysis of Pal drops

Visualization of Top 20 most common drops

Technologies Used

Python

Pandas

Plotly

Dash

Matplotlib

Seaborn

Jupyter Notebook

Project Structure
Palworld-Dashboard
│
├── data
│   └── Pals.csv
│
├── notebooks
│   └── Palworld's Pal Stats.ipynb
│
├── app.py
│
├── requirements.txt
│
└── README.md
Dataset

The dataset contains information about Palworld creatures including:

Name

Type

Rarity

HP

Melee Attack

Magic Attack

Defense

Speed attributes

Work skills

Price

Drops

Installation

Clone the repository:

git clone https://github.com/yourusername/palworld-dashboard.git

Navigate to the project folder:

cd palworld-dashboard

Install required libraries:

pip install pandas plotly dash matplotlib seaborn
Running the Dashboard

Run the application:

python app.py

Open your browser and go to:

http://127.0.0.1:8050/
Example Visualizations

The dashboard includes several interactive visualizations such as:

Bar charts

Scatter plots

Heatmaps

Box plots

Radar charts

Violin plots

Parallel coordinates plots

3D visualizations

Learning Outcomes

This project demonstrates:

Data analysis using Pandas

Interactive dashboards with Dash

Advanced data visualization using Plotly

Exploratory data analysis (EDA)

Visualization of complex relationships in datasets

Future Improvements

Add filtering options for Pal types and rarity

Deploy the dashboard online using Render / Heroku

Add machine learning predictions for Pal stats

Improve UI design and dashboard layout

Author

Devesh Das
B.Tech CSE Student
