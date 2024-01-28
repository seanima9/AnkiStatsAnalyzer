### Anki Spaced Repetition Analysis

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
Pandas for data manipulation
SQLite3 for database interaction
Matplotlib and NumPy for data analysis and visualization

## How to Run the Project
Ensure you have Python installed along with Pandas, SQLite3, Matplotlib, and NumPy libraries. Clone this repository and navigate to the project directory. Run the Jupyter Notebooks to see the analysis and visualizations. You will need to replace the db_path variable at the start of the notebook with your own collection.anki2 full file path.