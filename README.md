# Interference Analysis Project

This repository contains Python code for analyzing interference in Cambium network devices. The code reads data from CSV files, performs data cleaning and preprocessing, and flags instances of interference based on various criteria. The flagged data is then used to generate visualizations and insights into the interference patterns.
The flagged of interfernece is based on UL and DL MCS that is <=6, interference1 flag is based on issue counts = 3 including there is MCS/interfernece issue.
## Requirements
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Numpy

## Getting Started

### Prerequisites
Make sure you have Python installed on your machine. You can install the required packages using the following command:

```bash
pip install pandas matplotlib seaborn numpy


git clone https://github.com/yourusername/interference-analysis-project.git

cd interference-analysis-project

cd interference-analysis-project

python interference_analysis.py



This script reads data from CSV files, processes and cleans the data, performs interference analysis, and generates visualizations.

Data Files

CPE_interference_combined_21_30Jan.csv: CSV file containing interference data for CPE devices.
inventory_combined_21_30jan.csv: CSV file containing inventory data.
Additional data files may be required for specific tasks.

Output
The script generates various visualizations and insights into interference patterns, including:

Hourly trends of interference occurrences.
Frequency distribution of interference occurrences in the in-band and out-of-band.
Devices with interference on specific days.
Statistics on the number of days each device experienced interference.
