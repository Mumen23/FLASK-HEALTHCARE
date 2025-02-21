# Final Project: Data Collection and Analysis Tool

## Overview
This project involves developing a survey tool using Flask, MongoDB, and Python for data collection, processing, and visualization. The goal is to analyze income spending in preparation for a new product launch in the healthcare industry.

## Features
- **Web Development with Flask**: A simple webpage for data collection.
- **Data Storage with MongoDB**: Store user details including Age, Gender, Total Income, and Expenses.
- **Data Processing**: Convert stored data to CSV for analysis.
- **Data Visualization**: Analyze spending trends using Jupyter Notebook.
- **AWS Deployment**: Host the application on AWS.

## Installation & Setup
1. Clone this repository:
   ```sh
   git clone <repo-url>
   cd project-folder
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Set up MongoDB and configure the connection in `config.py`.
4. Run the Flask app:
   ```sh
   python app.py
   ```
5. Open `http://127.0.0.1:5000` in your browser.

## Data Processing
- Collected data is stored in MongoDB.
- Export data to CSV using the `User` class.
- Load CSV into Jupyter Notebook for analysis.

## Visualizations
- Show ages with the highest income.
- Display gender distribution across spending categories.
- Export charts for PowerPoint presentations.

## Deployment
- Deploy Flask app on AWS following standard deployment steps.

## Contributing
Feel free to fork this repository and submit pull requests.


