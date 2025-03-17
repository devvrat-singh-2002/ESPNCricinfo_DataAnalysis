### ESPNCricinfo_DataAnalysis



## Project Overview
This project focuses on analyzing the performance of players and teams during the T20 2022 Cricket World Cup. The goal was to generate insights using various Key Performance Indicators (KPIs) such as average runs, sixes and fours scored, strike rate, and more. The final output is an interactive dashboard created in Power BI, which visualizes the processed data to provide a comprehensive view of player and team performances.

## Implementation Steps
# 1. Web Scraping
~ Tool Used: Bright Data
~ Language: JavaScript

Process: Data was scraped from the ESPNcricinfo webpage, which contained tables with information about all matches and player performances during the T20 World Cup. JavaScript was chosen for its efficiency in handling browser-level tasks in JavaScript-heavy websites.

# 2. Data Preprocessing
~ Tool Used: Python (Pandas)

Process: The scraped data in JSON format was transformed and cleaned using Python's Pandas library. The data was then converted to CSV format for easier handling in subsequent steps.

# 3. Data Transformation and Cleaning in Power BI
Tool Used: Power BI (Power Query)

Process: The CSV data was imported into Power BI, where further data transformation and cleaning operations were performed using Power Query. This included delimiting operations, conditional column additions, etc.

# 4. Data Modeling
~ Tool Used: Power BI

Process: Necessary connections between fact and dimension tables were established in the Data Modeling view tab to prepare the data for measure creation and visualization.

# 5. Dashboard Creation
~ Tool Used: Power BI

Process: A dashboard mock-up was created to plan the visualization execution. Measures were created using DAX to define the required KPIs. The final version of the dashboard was developed iteratively, ensuring a clear and insightful representation of the data.

## Installation Instructions
To replicate or extend this project, follow these steps:

# Clone the Repository:
'''
git clone https://github.com/devvrat-singh-2002/ESPNCricinfo_DataAnalysis.git
cd ESPNCricinfo_DataAnalysis
'''
# Install Dependencies:

Ensure you have Python installed. Install the required Python packages using:

'''
pip install pandas
'''
# Install Power BI Desktop from the official Microsoft website:

Run the Web Scraping Script:

Navigate to the web_scraping directory and run the JavaScript scraping script using Node.js:

bash
Copy
node scrape_data.js
Preprocess the Data:

Run the Python preprocessing script:

bash
Copy
python preprocess_data.py
Open Power BI:

Import the processed CSV files into Power BI and follow the steps outlined in the Implementation Steps section to create the dashboard.

Usage Examples
Viewing the Dashboard: Open the Power BI file (T20_Analysis.pbix) to interact with the dashboard. Use filters to view specific player or team performances.

Analyzing KPIs: Explore various KPIs such as average runs, strike rate, and boundary counts to gain insights into player and team performances.

Contribution Guidelines
Contributions are welcome! Please follow these steps to contribute:

Fork the Repository:

Fork the repository to your GitHub account.

Create a Branch:

Create a new branch for your feature or bug fix:

bash
Copy
git checkout -b feature/your-feature-name
Commit Your Changes:

Commit your changes with a clear and descriptive commit message:

bash
Copy
git commit -m "Add your commit message here"
Push to the Branch:

Push your changes to the branch:

bash
Copy
git push origin feature/your-feature-name
Submit a Pull Request:

Open a pull request against the main branch of the original repository.

Contact Details
For any questions or feedback, please contact:

Name: Your Name

Email: your.email@example.com

GitHub: yourusername
