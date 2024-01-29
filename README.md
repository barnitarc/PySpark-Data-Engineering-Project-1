# Employee Data Analysis with PySpark
This project analyzes employee data using PySpark, focusing on insights derived from employee demographics, employment status, and training records. The analysis aims to provide valuable insights into employee performance, training effectiveness, and organizational dynamics.

## Project Files
* employee_data.csv: Contains detailed information about employees, including demographics, employment status, and performance ratings.
* training_and_development_data.csv: Provides records of training programs, outcomes, costs, and participant details.
## Dependencies
* PySpark: This project relies on PySpark for distributed data processing and analysis.
* Python 3.x: Ensure you have Python 3.x installed on your system.
* Jupyter Notebook: The analysis is presented in a Jupyter Notebook for interactive exploration.
## Usage
* Clone the repository to your local machine.
* Ensure you have the necessary dependencies installed, including PySpark and Jupyter Notebook.
* Open the Jupyter Notebook (Employee_Data_Analysis.ipynb) to explore the analysis.
* Execute each cell in the notebook to run the code and observe the results.
* Customize the analysis as needed or integrate it into your data pipeline.
## Project Overview
### Setup
* Initializes a Spark session and imports required libraries for data analysis.
### Exploratory Data Analysis on Employee Data
* Reads and examines the structure of the employee dataset.
* Cleanses date fields and performs basic data cleaning operations.
* Explores employee demographics and employment status.
* Identifies duplicates and inspects unique values for specific columns.
### Employee Data Analysis
* Identifies the highest-rated employee in each department within every zone.
* Determines the count of active employees in each business unit.
### Exploratory Data Analysis on Training Data
* Loads and inspects the training and development dataset.
* Cleanses date fields and identifies unique training programs and locations.
* Investigates the most frequent locations for training sessions and different training outcomes.
### Training Data Analysis
* Calculates the total cost for each training program.
* Determines the count of unique trainers involved in the programs.
* Identifies employees who successfully completed the highest-costing training programs.
### Employee and Training Data Integration
* Matches employees with their respective training records to analyze training outcomes and dates concerning employee start dates.
* Calculates the duration of employment for each employee.
* Investigates employees under Performance Improvement Plans (PIP) across divisions and their associated training completions.
## Notes
* This project is designed for exploratory data analysis and insights generation. It can be extended for further analysis or integrated into larger data pipelines.
* Make sure to customize file paths and configurations based on your environment and data source locations.
* Feel free to modify the code and analysis to suit your specific requirements or business objectives.

# Questions answered:
1. Find highest rated employee in every department in each zone
2. Find how many active employees are in each business unit
3. Find the most frequent location trainings took place
4. find total cost for each training program
5. find name,dob,email, supervisor of employees who have successfully completed the each highest costing trainings programs.
6. find after how many days each employee took their training after joining, what training they took and whats was the outcome
7. find how many days each employee worked/is working in the company
8. how many employees are in PIP in each divisions and how many training were completed/passed for those
 
 -- feel free to clone and add more questions here. Thanks
