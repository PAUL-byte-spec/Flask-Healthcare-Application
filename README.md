# Flask-Healthcare-Application

# Healthcare Survey Tool with Data Analysis and Visualization
This repository contains the source code for a web application that collects data from participants in the healthcare industry regarding their income and spending habits. The collected data is then analyzed and visualized to gain insights that can be used for developing new healthcare products.

# Project Components:

# Web Development:
  * Uses Flask to create a user-friendly web page for data collection.
  * Employs checkboxes and input fields for collecting details like age, gender, income, and categorized expenses (utilities, entertainment, school fees, shopping, healthcare).
  * Data Storage:
  * Leverages MongoDB to store user data securely.
  * Creates a document structure to store collected information efficiently.
# Data Processing:
  * Utilizes Python or R to process and analyze the data.
  * Creates a "User" class to represent individual participants and their information.
  * Loops through collected data and stores it in a CSV file for further analysis.
# Data Visualization:
  * Employs Jupyter notebook for data analysis and visualization.
  * Generates visualizations like:
  * Bar chart showing ages with the highest income.
  * Stacked bar chart illustrating gender distribution across spending categories.

# Prerequisites:
* Python 3.x
* Flask
* pymongo (for MongoDB connection)
* Jupyter Notebook



git clone https://github.com/<your-username>/healthcare-survey-tool.git
Use code with caution.
Install dependencies:

cd healthcare-survey-tool
pip install -r requirements.txt
Use code with caution.

# Configure MongoDB connection:
Replace the placeholder connection details in the code with your actual MongoDB connection information (hostname, port, database name, collection name).

# Run the application:
* python app.py
* Use code with caution.

# Access the application:
 * Open your web browser and navigate to http://127.0.0.1:5000/ to access the survey form.

# Analyze and visualize data:
Open the provided Jupyter notebook and follow the instructions within for data analysis and visualization.

# Further Notes:
This project serves as a starting point and can be customized and extended based on your specific needs.
Consider implementing additional features like user authentication, data filtering, and advanced data analysis depending on your requirements.
Ensure proper data security practices are followed, especially when handling sensitive information like income.
Contributing:

We welcome contributions and improvements to the project. Please submit pull requests with your proposed changes.
