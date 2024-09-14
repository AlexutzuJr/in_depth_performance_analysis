# Project Overview

This project performs comprehensive data analysis on Indian Premier League datasets using PySpark for large-scale data processing and manipulation. It covers key aspects such as top-scoring batsmen, economical bowlers, and the impact of toss on match outcomes. The analysis also includes visualizations using Matplotlib and Seaborn to gain insights into the IPL match performance over various seasons.

**Project Steps**
* Data ingestion
* Data cleaning and transformation
* SQL queries and insights
* Visualization

# Local Setup

## Installation

To set up the environment and run the project, follow these steps:

* Ensure that you have the following Python packages installed: pip install pyspark matplotlib seaborn.
* Download the IPL datasets from your desired source or use the provided S3 path in the project.

# Usage
Data analysis with Spark:

* Run the data_analysis_spark.ipynb notebook to load the datasets and perform the analysis.
* Execute the SQL queries within the notebook to retrieve insights such as top-scoring batsmen and economical bowlers.
* Explore the visualizations generated using Matplotlib and Seaborn.
  
SQL queries:

* You can run additional Spark SQL queries by creating temporary views from the dataframes and executing them in the notebook.

Visualization:

* After running the analysis, visualizations are generated automatically, such as: top economical bowlers in powerplay overs, toss impact on match outcomes, average runs scored by players in winning matches.

Modifications:

* You can modify the analysis and queries in the notebook to extract other insights or visualize different aspects of the data.
