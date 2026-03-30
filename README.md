## Project: Collecting Job Data Using APIs
This project demonstrates how to programmatically interact with REST APIs to retrieve, process, and analyze professional job market data. It transitions from basic API connectivity tests using space exploration data to a focused analysis of technical roles and geographic demand across the United States.

## Getting Started
1. Clone the repository

## Bash
git clone https://github.com/yourusername/job-data-api-project.git
2. Navigate to the project folder

## Bash
cd job-data-api-project
3. Install required libraries
Ensure you have Python installed, then run:

## Bash
pip install requests pandas openpyxl pillow
Note: These libraries handle API requests, data manipulation, and Excel file generation.

4. Launch Jupyter Notebook

## Bash
jupyter notebook
Open Collecting Data Using APIs.ipynb to view the analysis and code execution.

## Project Insights
## Key Takeaway: 
Automating data collection via APIs allows for real-time analysis of job market trends, significantly reducing the manual effort required to track demand for specific technical skills.

## Skills Learned:

* API Integration: Utilizing the requests library to fetch JSON data from REST endpoints.

* Data Parsing: Navigating complex nested JSON structures to extract specific attributes like Key Skills and Location.

* Data Cleaning: Implementing case-insensitive filtering to accurately count technology mentions within datasets.

* Automated Reporting: Using pandas and openpyxl to programmatically generate structured Excel reports.

* Technical Problem Solving: Designing functions to iterate through large datasets and compile aggregate statistics.

## Future Enhancements
* Regex Refinement: Implement Regular Expressions (Regex) to ensure single-letter technologies like "C" do not capture unrelated strings.

* Data Visualization: Integrate Matplotlib or Seaborn to create visual dashboards of job demand by city.

* Multi-Source Aggregation: Expand the script to pull and compare data from multiple job board APIs simultaneously.

## Contact
genesisadriel.segovia@outlook.com
