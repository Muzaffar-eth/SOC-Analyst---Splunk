Title: SOC Analyst Splunk Project: Analyzing Malicious IP Addresses from Botsv3 Dataset

Description:
This project focuses on analyzing a dataset named Botsv3, sourced from GitHub, to identify and track malicious IP addresses. Leveraging Splunk, along with the AbuseIPDB tool for IP geolocation, I conducted in-depth analysis to understand the origin and frequency of malicious IP activities. This README provides an overview of the project's objectives, methodologies, findings, and instructions for replicating the analysis and visualizing the results using Splunk dashboards.

Objectives:

Analyze the Botsv3 dataset to identify malicious IP addresses.
Determine the geographic distribution of these malicious IPs.
Visualize the findings through interactive Splunk dashboards for actionable insights.
Dataset:

Name: Botsv3
Source: GitHub
Description: Contains a collection of IP addresses associated with malicious activities, sourced from various threat intelligence feeds.
Methodology:

Data Collection: The Botsv3 dataset was acquired from GitHub.
Data Enrichment: Utilized Splunk for data enrichment and preprocessing.
IP Geolocation: Leveraged the AbuseIPDB tool to determine the country of origin for each malicious IP address.
Analysis: Conducted analysis to identify the frequency of malicious IP occurrences and their corresponding countries.
Visualization: Created interactive dashboards in Splunk to visualize the analysis results.
Findings:

Identified a significant number of malicious IP addresses within the Botsv3 dataset.
Determined the top countries from which these malicious IPs originated.
Uncovered patterns and trends in malicious IP activities over time.
Replicating the Analysis:

Data Acquisition: Download the Botsv3 dataset from GitHub.
Data Ingestion: Ingest the dataset into Splunk for analysis.
Enrichment: Utilize the AbuseIPDB tool or similar services to enrich IP addresses with geolocation data.
Analysis: Conduct analysis to identify malicious IPs and their associated countries.
Visualization: Create Splunk dashboards to visualize the analysis results.
Splunk Dashboard:

Visualization Components:
Bar chart: Displays the top countries with the highest number of malicious IP addresses.
Table: Lists detailed information about each malicious IP address, including its frequency and originating country.
Map: Geographically visualizes the distribution of malicious IP addresses worldwide.
Interactive Features:
Drilldown: Allows users to drill down into specific countries or IP addresses for detailed analysis.
Time Range Selector: Enables users to filter data based on a specific time range for dynamic insights.
Conclusion:
This project showcases the power of Splunk in analyzing and visualizing malicious IP address data from the Botsv3 dataset. By leveraging geolocation information and interactive dashboards, SOC analysts can gain actionable insights to enhance cybersecurity defense mechanisms and mitigate threats effectively.

References:

Botsv3 Dataset: GitHub Repository
AbuseIPDB: Official Website
Splunk Documentation: Official Website
Geolocation APIs: AbuseIPDB API
