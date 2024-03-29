# Anki Spaced Repetition Analysis 🐢

## Project Overview

This project presents a comprehensive data-driven analysis of the Anki spaced repetition system (SRS). Using Python for data extraction, analysis, and visualization, the project investigates the effectiveness of Anki in facilitating learning and memory retention. Key focus areas include success rates, ease factors, response times, and their correlations with review intervals and repetition counts.

## Objective

The primary objective is to understand how different variables within Anki's spaced repetition algorithm correlate with learning effectiveness. The analysis aims to uncover patterns and insights that could lead to improvements in both the SRS algorithm and user study strategies.

## Methodology

Data Extraction: Data is extracted from Anki's SQLite database, focusing on user review logs and card metadata.
Data Preprocessing: The data undergoes cleaning and transformation, including timestamp conversion and handling of anomalous entries.
Data Analysis: Various aspects such as success rates over time, ease factor stability, and time taken for responses are analyzed.
Visualization: Data is visualized using matplotlib to illustrate key trends and patterns.

## Key Findings

Success rates improve and answer times decrease as intervals between reviews increase.
There's a negative correlation between time taken to answer and success rate.
Certain cards appear to get 'stuck' at low interval distances, indicating potential inefficiencies in the SRS algorithm.

## Technologies Used
Python
Jupyterlab
Pandas for data manipulation
SQLite3 for database interaction
Matplotlib and NumPy for data analysis and visualization

## How to Run the Project
Ensure you have Python installed along with Pandas, SQLite3, Matplotlib, Pyarrow, and NumPy libraries. Clone this repository and navigate to the project directory. Run the Jupyter Notebooks to see the analysis and visualizations. You will need to replace the db_path variable in cell 3 with your own collection.anki2 full file path, typically located in AppData/Roaming/Anki2/User 1/collection.anki2.
All packages in correct version can be installed using pip install -r requirements.txt. It is recommended to do this in a venv.

## Documentaion
For more information on this project and its findings please refer to our documentation: 
- [Anki.ipynb Documentation](https://planet-perch-311.notion.site/Documentation-for-Anki-Analyzer-2bdf016eef3d441f9345c22a35c3ead3?pvs=4)