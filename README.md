# Project: Vaccine Distribution in Finland

## General description

The project topic is about COVID-19 vaccine distribution and treatment in Helsinki, Finland. 
The purpose of this project is to build a database that keeps track of different vaccine types, 
transportation of vaccine batches, treatment plans and patient data. The project uses sample data 
provided in the database course at Aalto University.

This database project can be beneficial to different user groups 
– the government, healthcare centers, vaccination centers, and vaccine manufacturers, to name a few. 


## Instructions

### Step 1: Clone the remote repository to your local device.

```shell
git clone https://github.com/thngcode/vaccine_distribution_project.git
```

### Step 2: Install and activate a virtual environment on your device.

```shell
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt  
```

### Step 3: Install the required external libraries.

```shell
pip install -r requirements.txt  
```

### Step 4: Copy the credentials.json file to the /code folder, or manually create the file. 

The format of the file should follow {"database": "###", "user": "###", "password": "###", "host": "###", "port": ###}, where you
need to replace ### with your own information.

### Step 5: Run the Python file populate_tables_script.py to create and populate the database.

```shell
python3 populate_tables_script.py
```

The database is now ready for use.

## Database optimization 
After designing the database, data normalization rules are applied to evaluate 
if the tables are structured correctly and effectively. After that, appropriate changes are made 
to optimize the database performance.

## Data analysis
As part of the project, different analyses are performed and produce data visualizations to discover patterns and insights which could practically support data-driven decision making of the user groups. 
The report is available as a [Jupyter Notebook](./code/data_analysis.ipynb) and [PDF file](./analysis_report.pdf).


