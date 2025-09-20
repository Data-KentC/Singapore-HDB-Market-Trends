# Singapore-HDB-Market-Trends

# HDB Resale Price Analysis

### Project Overview
This project uses publicly available HDB resale transaction data to analyze and visualise key market trends. The goal is build a ETL pipeline and to uncover high-level insights from the data on key influences on resale prices.

### Technologies Used
-   **Python**: The primary language for building the ETL pipeline data analysis and visualisation.
-   **Libraries**: `Pandas` for data manipulation, `Matplotlib`, `Seaborn` and Power BI for data visualisation.
-   **Database**: Postgresql to store the clean data
-   **Other Tools**: Jupyter Notebooks for interactive analysis and presentation.

### Project Structure
-   `data/`: Contains the raw and processed datasets used in the analysis.
-   `notebooks/`: Includes the Jupyter notebooks with the full data analysis workflow, from data ingestion to visualization.

### Key Findings
* Identified a strong correlation between flat storey height and transaction resale prices.
* Proven Bala's curve in leasehold property exists. 
* Visualised how average resale prices differ across different towns. This have an impact on resale prices.

### Future Work
This project lays the groundwork for more advanced analysis. Future work will focus on building a machine learning model to predict HDB resale prices based on a variety of features, expanding on the insights gained from this initial analysis.
