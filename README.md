# MFG_598_Engg_Project

# Amrapali_W_MFG598
This repository contains the source code for the project for MFG 598 by Amrapali Milind Waghmare

**Project Description**
The objective of project is to Analyze the Top Largest US companies by revenue is to gather financial and operational information about the largest companies in the United States. The project aims to provide insights into the revenue, size, growth patterns, industry distribution, and employment data by using data extraction techniques.
This project develops an interactive dashboard to explore and analyze data related to largest companies in the United States by revenue. Projects combines web scarping, data cleaning, visualization, and advanced clustering techniques to provide comprehensive analytical tool.
The dashboard assists data analysts, busniess professionals, and academic researchers in understanding in industry trends, corporate growth,and employment dynamics among the top U.S corporation.

**Features**
Data Extraction and Processing:
Automated Web Scraping: The dashboard automatically extracts the latest data from Wikipedia, ensuring up-to-date information is always available.
Data Cleaning and Preparation: Implements preprocessing steps to convert text data into numerical formats, splits location data into city and state, and encodes categorical variables for analysis.
Interactive Visualization:
Top Industries by Revenue: Visualizes the top 10 industries by total revenue, helping identify which sectors are dominating the U.S. economy.
Companies by Revenue Growth: Displays the top 10 companies based on revenue growth rate, highlighting rapidly growing companies.
Companies by Employee Count: Shows the top 10 companies by number of employees, providing insights into major employers.
Advanced Clustering Techniques:
K-Means Clustering: Applies K-means clustering to segment the companies based on financial and workforce metrics, shown in a 3D plot.
Agglomerative Clustering: Performs hierarchical clustering to explore data structures and relationships in a 3D dendrogram (intended but requires implementation detail).
DBSCAN Clustering: Utilizes Density-Based Spatial Clustering of Applications with Noise to identify core groups of high-density companies, effectively handling outliers.
Industry-Specific DBSCAN: Offers customized DBSCAN clustering for selected industries, enabling detailed sector analysis.
User Interaction:
Dynamic Dropdown Menus: Users can choose from various analysis and visualization options via dropdown menus, making the dashboard versatile and user-friendly.
Real-Time Updates: The dashboard updates visualizations instantly based on user selections, providing a seamless interaction experience.

**Usage**
To run the "Integrated Data Visualization and Clustering Dashboard" project developed with Python and Tkinter, you'll need to follow several steps to set up your environment and execute the program. Here’s a step-by-step guide on how to do this:

Prerequisites
Ensure you have Python installed on your computer. You can download Python from python.org. This project also requires several Python libraries, including pandas, matplotlib, sklearn, seaborn, and BeautifulSoup. You can install these packages using pip.

Step 1: Install Required Libraries
Open your command prompt (Windows) or terminal (macOS, Linux) and install the required libraries using pip:
pip install pandas matplotlib scikit-learn seaborn beautifulsoup4 requests

Step 2: Prepare the Code
You can either write the code in a Python script (.py file) or run it in an interactive environment like Jupyter Notebook. Here, I'll explain how to run it as a script:

Open a text editor or an IDE (like Visual Studio Code, PyCharm, or even a simple text editor like Notepad++).
Copy the entire code provided in the discussions (ensure you have the complete script that includes data scraping, data processing, and the Tkinter dashboard).
Save the file with a .py extension, for example, data_dashboard.py.

Step 3: Run the Script
Open your command prompt or terminal.
Navigate to the directory where your script is saved. For example, if it's saved in C:\Users\YourUsername\Projects, you would type:
cd C:\Users\YourUsername\Projects

Run the script by typing:
python data_dashboard.py

Step 4: Interact with the Dashboard
Once the script is running, the Tkinter GUI should appear. You can interact with the dropdown menus to select different types of data visualizations and clustering results. The dashboard allows you to view:

Top 10 industries by revenue.
Top 10 companies by revenue growth.
Top 10 companies by number of employees.
Results of clustering analyses (K-Means, DBSCAN, Agglomerative Clustering).
Industry-specific clustering using DBSCAN.

**Technologies Used**
Python: For backend operations including data scraping, cleaning, and clustering.
Tkinter: Used for building the GUI to ensure it is lightweight and easy to deploy.
Matplotlib and Seaborn: For generating static and interactive plots.
Scikit-learn: Provides robust clustering algorithms for data analysis.
Beautiful Soup: For scraping HTML content and extracting data.