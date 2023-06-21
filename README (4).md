
# Survey Monkey Data Cleaning, Transformation and Merging Project: Unveiling Workforce Insights






This project analyzes survey data to extract insights on employee demographics, including division, position level, generation, gender, tenure, and employment type within an organization. 

By merging and cleaning the data, filtering and aggregating survey responses, it provides HR professionals and management teams with valuable information for decision-making and strategy development. 

The results are saved in an Excel file for easy access and further utilization.


## Screenshots
## Description

* The project involved working with survey data obtained from Survey Monkey. Python and the pandas library were utilized for data manipulation.

* The survey data was read from an Excel file.

* Irrelevant columns were dropped from the dataset.

* The dataset was transformed from a wide format to a long format using melt().

* A separate sheet containing survey questions was imported and cleaned.

* The cleaned question dataset was merged with the melted dataset, adding question text to each row.

* The number of respondents for each question and subquestion was calculated.

* The count of respondents with the same answer for each question and subquestion combination was determined.

* The calculated insights were merged back into the main dataset.
## Dataset

* Download the dataset from github profile:

* https://rb.gy/mvi8b
## Installation

### Requirements

To run the project in .ipynb format, you need to follow the following installation requirements and setup steps:

### Installation Requirements:
1. **Python**: Ensure that Python is installed on your system. You can download the latest version of Python from the official Python website.

2. **Jupyter Notebook**: Jupyter Notebook is required to run the project in .ipynb format. Install it using pip, the Python package installer, by running the following command in your command prompt or terminal:
   ```
   pip install jupyter notebook
   ```

3. **pandas**: The project heavily utilizes the pandas library for data manipulation. Install it using the following command:
   ```
   pip install pandas
   ```

4. **openpyxl**: Since the project involves working with Excel files, the openpyxl library is required. Install it with the following command:
   ```
   pip install openpyxl
   ```

### Project Setup Steps:
1. **Clone or Download the Project**: Clone the project repository to your local machine or download and extract the .ipynb project file.

2. **Launch Jupyter Notebook**: Open your command prompt or terminal, navigate to the directory where the .ipynb file is located, and launch Jupyter Notebook by running the following command:
   ```
   jupyter notebook
   ```

3. **Open the Project**: In the Jupyter Notebook interface that opens in your web browser, click on the .ipynb file to open it.

4. **Run the Project**: Within Jupyter Notebook, you can run each cell individually by clicking on it and then pressing Shift + Enter. Alternatively, you can run all the cells at once by selecting "Run All" from the "Cell" menu.

By following these steps, you will have the necessary installations in place and be able to set up and run the project using Jupyter Notebook with the provided .ipynb file.
## Features

The important features of the project can be summarized as follows:

1. **Data Manipulation**:
   - Extensive data manipulation using the pandas library in Python.
   - Dropping irrelevant columns from the survey dataset.
   - Transforming the dataset from wide format to long format using the `melt()` function.

2. **Data Cleaning and Merging**:
   - Cleaning and merging a separate sheet containing survey questions.
   - Merging the cleaned question dataset with the main dataset to add question text to each row.
   - Ensuring data consistency and accuracy through cleaning and merging operations.

3. **Analysis and Insights**:
   - Calculating the number of respondents for each question and subquestion.
   - Determining the count of respondents with the same answer for each question and subquestion combination.
   - Merging the insights back into the main dataset for analysis.

4. **Exporting Results**:
   - Exporting the final merged dataset, enriched with question text and insights, to an Excel file.
   - Facilitating easy sharing and dissemination of the analyzed data.

5. **Tools and Language Used**:
   - **Python**: The project is implemented using the Python programming language.
   - **pandas**: The pandas library is utilized for efficient data manipulation and analysis.
   - **openpyxl**: The openpyxl library is used for working with Excel files.


## Authors

- [@RizwanaFahim](https://github.com/RizwanaFahim)

