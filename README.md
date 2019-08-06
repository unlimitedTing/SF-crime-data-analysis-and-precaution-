# SF-crime-data-analysis-and-precaution
## Summerize
Analyzed the crime record in SF from 2013 to 2018, 811784 rows in total, to give insights and precaution of crimes that happened in SF
## Step By Step
- Built data ETL pipeline via SparkSession on Databricks, analyzed data descriptively by conducting OLAP via PySpark and SQL
- Trained k-means on spatial location for different crime categories to cluster them by constructing machine learning pipeline via Spark ML and draw elbow figure to find the best k value for each one
