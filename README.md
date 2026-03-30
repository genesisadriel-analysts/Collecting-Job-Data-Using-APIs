📊 Project: Collecting Job Data Using APIs
📌 Overview
This project demonstrates the end-to-end process of programmatically interacting with REST APIs to retrieve, process, and analyze professional job market data.

The workflow transitions from foundational API connectivity tests (using space exploration data) to a focused analysis of technical roles and geographic demand across the United States. It highlights the power of automation in replacing manual market research with real-time data ingestion.

🎯 Key Objectives
API Orchestration: Authenticate and fetch data from live REST endpoints using the requests library.

Granular Data Parsing: Navigate complex, nested JSON structures to isolate high-value attributes like Key Skills and Geographic Location.

Case-Insensitive Analytics: Implement robust filtering to accurately count technology mentions across diverse job descriptions.

Automated Reporting: Programmatically generate structured .xlsx reports using pandas and openpyxl.

🛠️ Tech Stack & Skills
Language: Python

Libraries: * requests (HTTP Interaction)

pandas (Data Manipulation & Cleaning)

openpyxl (Excel Report Generation)

Pillow (Image Handling)

Environment: Jupyter Notebook

🚀 Execution Guide
1. Environment Setup
Clone the repository and install the necessary dependencies:

Bash
git clone https://github.com/yourusername/job-data-api-project.git
cd job-data-api-project
pip install requests pandas openpyxl pillow
2. Run the Analysis
Launch the notebook environment to view the code execution and data insights:

Bash
# Launch Jupyter
jupyter notebook
Open: Collecting Data Using APIs.ipynb

🧠 Project Insights & Skills Learned
Technical Problem Solving: Designed iterative functions to traverse large datasets and compile aggregate statistics.

Data Cleaning: Developed logic to normalize data, ensuring that varied naming conventions for technologies (e.g., "python" vs "Python") are captured accurately.

Efficiency: Automated a workflow that would typically take hours of manual "copy-pasting" into a script that runs in seconds.

🔮 Future Roadmap
Regex Refinement: Implement Regular Expressions to ensure high-precision filtering (e.g., preventing "C" from matching inside "Cloud").

Dynamic Visualization: Integrate Matplotlib or Seaborn to generate heatmaps of job demand by city.

Multi-Source Aggregation: Expand the pipeline to consolidate data from multiple job board APIs (LinkedIn, Indeed, etc.) simultaneously.

📩 Contact
Genesis Adriel Segovia Email: genesisadriel.segovia@outlook.com
