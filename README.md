# Analysis of a Ticketing System

This project analyzes the data that my employer's ticketing system has collected in 2022 and 2023. I exported this data directly from the system and anonymized sensitive data. I have created visualizations based on this data in Tableau [here](https://public.tableau.com/app/profile/emma.ortiz/viz/TicketingSystemMetrics/FinalDashboard#1)!

# Instructions

#### Clone the repository to your machine:

```
git clone https://github.com/eortiz716/dataproject.git
```
#### Install a virtual environment in the cloned repository:

```
python3 -m venv venv
```
#### Activate the virtual environment:

On Windows:
```
venv\Scripts\activate
```
On macOS and Linux:
```
source venv/bin/activate
```

#### Installing Dependencies:

Ensure your virtual environment is activated.
Install the requirements.txt file:
```
pip install -r requirements.txt
```

# Important Note

You will notice some of code in the Jupyter Notebook file is commented out. I included this code to show what I used to anonymize the data without giving you, the user, access to said sensitive data. I have included in the repo the merged_data.csv file that is the result of the anonymizing and merging. This file can be used for the last section of code to generate a column in the table with additional information.

# Features

1. Read two CSV files
2. Clean data and perform a pandas merge with the two data sets, then calculating a new value based on the new data set
3. Make a Tableau dashboard to display data
4. Utilze a virtual environment and include instructions in README on how to set it up
5. Annotate code clearly