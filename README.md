# London Bike Sharing Data Processing Script

![image](https://github.com/user-attachments/assets/d9d340ab-b5b8-4545-9c5d-935cb3951123)




## Overview

This script automates the process of downloading, cleaning, and organizing the London Bike Sharing Dataset from Kaggle. The cleaned data is then exported to an Excel file, ready for visualization or further analysis.

## Features

**Automated Data Download:** Downloads the dataset directly from Kaggle using the Kaggle API.

**Data Cleaning:** Checks for missing values, duplicates, and inconsistent data entries.

**Data Transformation:** Renames columns, organizes the data for better readability, and prepares it for analysis.

**Export to Excel:** Saves the cleaned and processed data into an Excel file for easy visualization and further analysis.

## Requirements

- Python 3.x
- Pandas
- Kaggle API

## Installation

**1. Clone the Repository:**
```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

**2. Install Required Packages: Ensure you have pandas installed:**
```
pip install pandas
```

**3. Kaggle API Setup:**

Sign up or log in to Kaggle.

Go to your account settings and select "Create New API Token" to download a kaggle.json file.

Place kaggle.json in the appropriate location, such as ~/.kaggle/ for Linux/MacOS or C:\Users\<YourUsername>\.kaggle\ for Windows.
```
pip install kaggle
```

## Tableau Visualization

I have created a detailed visualization of the cleaned data in Tableau. This visualization includes:

- **Trend Analysis**: Visualization of bike usage trends over time.
- **Correlation Analysis**: Heat map showing the relationship between wind flow and temperature and their impact on cycling frequency.

### View the Visualization

You can view the Tableau visualization on my Tableau Public profile:

- [View the Visualization on Tableau Public](https://public.tableau.com/app/profile/marcelina.szczygiel/viz/LondonBikeRides_17252016809120/Dashboard1)

## Usage

**1. Run the Script:**
- Execute the script to download, clean, and process the dataset:
```
python your_script_name.py
```

**2. Data Processing:**

The script will:
- Download the dataset from Kaggle.
- Check for duplicates, missing values, and other inconsistencies.
- Rename columns and reformat the data.
- Save the cleaned data to an Excel file in a specified directory.

**3. Output:**

The final cleaned dataset will be saved as an Excel file named cleaned_london_bike_sharing.xlsx in the output directory. 


## Data Source

This project uses data provided by Transport for London (TfL) under the following license terms:

- The data is provided under a modified version of the Open Government Licence (OGL) 2.0.
- You can view the full license [here](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset) or on the [TfL website](https://tfl.gov.uk).
- **Attribution Requirements**:
  - Acknowledge TfL as the source of the Information by including the following attribution statement: 'Powered by TfL Open Data'.
  - Acknowledge that this Information contains Ordnance Survey derived data by including the following attribution statement: 'Contains OS data © Crown copyright and database rights 2016' and Geomni UK Map data © and database rights [2019]'.

Please ensure you comply with these terms if you use or distribute the data.



