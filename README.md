# Spotify_Data_Pipeline
This is an end-to-end pipeline which will fetch data using the spotify api and aws lambda daily scheduled using an Event Trigger and store it as a csv in AWS S3 Bucket. This data will then be transformed using a Jupyter Notebook and sent to a postgre database staging table. The staging tables have defined Functions and Triggers that are activated once the data is inserted and will be inserted into their respective tables based on snowflake design.

Pipeline Design
![Spotify Data Pipeline](https://github.com/user-attachments/assets/b4ed2571-e162-41ce-816f-a06614257084)

Databse Table ERD
![Postgre Table ERD](https://github.com/user-attachments/assets/ceda1c7e-5be4-4908-a162-7ae33768c310)
