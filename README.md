# BiciMAD Group 13

This is the Bicimad assignment by Pablo Fernández, Gabriel Alba amd Joaquín Velarde.


# BICIMAD Data Analysis

This repository contains data and scripts related to the analysis of BICIMAD, a public bicycle sharing system in Madrid, Spain. The repository includes a folder, `datos`, which contains the extracted information from the registers of BICIMAD for the years 2017 and 2018, and of March of 2019. Additionally, the repository includes a PDF document, `Memoria_Práctica_BICIMAD___PRPA.pdf`, which provides a detailed explanation of the study and the business case, showcasing the insights obtained from the analysis. The folder `programa` contains all the necessary items to execute the analysis, although we had problems importing the json documents, as they are too heavy. 

## Files
- `datos`: This folder contains all the information we extracted from our analysis

- `datos_2017`: This folder (inside `datos`) contains the data extracted from the registers of BICIMAD for the year 2017. It includes various attributes such as timestamp, user ID, bicycle ID, station ID, and other relevant information.

- `datos_2018`: This folder (inside `datos`) contains the data extracted from the registers of BICIMAD for the year 2018. Similar to the previous file, it includes timestamp, user ID, bicycle ID, station ID, and additional details.

- `pruebasMarzo2019`: This file (inside `datos`) contains the data extracted from the registers of BICIMAD for the year 2018. Similar to the previous file, it includes timestamp, user ID, bicycle ID, station ID, and additional details.

- `Memoria_Práctica_BICIMAD___PRPA.pdf`: This PDF document provides a comprehensive overview of the study conducted on BICIMAD data. It includes an explanation of the data analysis process, methodologies used, and the insights gained from the analysis. The document also presents a business case based on the findings.

- `bicimad.py`: This Python script (inside `programa`) was utilized to extract and process the BICIMAD data using the PySpark framework. The script includes various functions and algorithms to clean, transform, and analyze the data, providing valuable insights into the usage patterns and trends of the BICIMAD system.
It requires a folder bicimad_data by its side with the information we want to analyze. 

- `Cluster_Ejecucion.png`: This image shows the upload and execution of the script in the Raspberries PI Cluster

## Usage

To use the data and script provided in this repository, follow the steps below:

1. Clone the repository using the following command:

```
git clone https://github.com/your-username/bicimad-data-analysis.git
```

2. Ensure that you have the necessary dependencies installed, including PySpark.

3. Open the `bicimad.py` script in a Python IDE or text editor to view and modify the code if needed.

4. Go to the Bicimad public website and download a .json file with the information of a month of your liking (before 2020, as they changed the format of their data). Download the json file into the `bicimad_data` folder, which you must replace for the `bicimad_data` file (inside the folder `program`)

5. Execute the script using a PySpark environment to obtain insights from the BICIMAD data.

## Contribution

Contributions to this repository are welcome. If you have any improvements or suggestions, please feel free to create a pull request or raise an issue.
