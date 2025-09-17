 Salon & Spa Analytics – Databricks Project
This project analyzes Salon & Spa appointment data using PySpark on Databricks.
It provides insights into:
•	Revenue trends by service type
•	Customer behavior (cancellations and no-shows)
•	Staff utilization metrics
•	Peak booking hours
The project demonstrates end-to-end data analysis and visualization in Databricks using a sample dataset.
________________________________________
 Dataset
The dataset used is salon_spa_appointments.csv with 75 sample records.
Columns include:
•	Appointment ID – Unique appointment number
•	Customer ID – Unique ID for customers
•	Service Type – Type of service (Haircut, Spa Therapy, Facial, etc.)
•	Staff ID – Staff member assigned
•	Booking Timestamp – Date and time of booking
•	Status – Completed, Cancelled, or No-show
•	Price – Service price (₹)
•	Duration (minutes) – Duration of service
________________________________________
 Project Workflow
1.	Upload dataset into Databricks
2.	Create table salon_spa_appointments
3.	Load data into PySpark DataFrame
4.	Perform analysis on:
o	Revenue per service type
o	Frequent cancellers and no-shows
o	Staff utilization
o	Peak booking hours
5.	Build interactive dashboards with Databricks visualizations
We want to analyze salon & spa performance using appointment data to answer:
Revenue Trends – Total revenue per service type
Customer Behavior – Identify frequent cancellers/no-shows.
Staff Utilization – Average appointment duration per staff.
Peak Hours – When customers usually book appointments.
