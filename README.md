# Geographical_Hierarchy_Processor
The **Geographical_Hierarchy_Processor** is a Python script designed to process geographic hierarchies with a parent-chile id system and add coordinates to location data.<br>
It connects to a PostgreSQL database, fetches data using SQL queries, processes hierarchical relationships, and enriches the data with latitude and longitude using the OpenStreetMap Nominatim API.<br>
The processed data can be saved back to the database or exported as CSV files.

# .env file format
  database = "your_database"  # Replace with your database<br>
  user = "your_username"  # Replace with your username<br>
  password = "your_password"  # Replace with your password<br>
  host = "your_host"  # Replace with your database host<br>
  port = "your_port"  # Replace with your database port<br>
  SearchID = "ITC3" # Search ID for Liguria
