# 2016 Presidential Polling Data Analysis

This project performs a comprehensive data analysis and visualization of the 2016 US presidential general election polling data. Using Python, Pandas, and Seaborn, the analysis walks through the full lifecycle of a data science project, from data ingestion to final visualization.

## 📊 Project Overview

The objective is to explore polling trends leading up to the 2016 election, cleaning the raw dataset, and visualizing the performance of candidates (Clinton and Trump) across different polling grades and dates.

### Key Features
- **Data Cleaning**: Handling datetime conversions and missing values.
- **Data Transformation**: Reshaping polling data for comparative analysis.
- **Exploratory Data Analysis**: Analyzing poll quality (grades) and their impact.
- **Visualizations**: Time-series line plots and categorical count plots using Seaborn.

## 📁 Project Structure

- `ex_12-christian_bongiorno_polling.ipynb`: The primary Jupyter Notebook containing the analysis.
- `data/`: Contains the source dataset (`president_general_polls_2016.csv`).
- `requirements.txt`: Python dependencies for the project.

## 🛠️ Setup & Installation

To run this analysis locally, ensure you have Python installed, then follow these steps:

1. **Clone or download** this repository.
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch the Notebook**:
   Open `ex_12-christian_bongiorno_polling.ipynb` in Jupyter Lab, Jupyter Notebook, or VS Code.

## 📝 Case Study Requirements

This project follows the data analysis process outlined in *Murach's Python for Data Science*. The following requirements are addressed within the notebook:

### 1. Goal Setting
Define the analysis goals and target audience.

### 2. Questions
Identify at least 5 key questions to answer.

### 3. Five Phases of Data Analysis
Identify each stage of the data analysis process and include a minimum of a paragraph of text/comments explaining the process for each of the steps. 
The more information you can include the better!

#### Get the data
Load the [polling data](data/president_general_polls_2016.csv) from a CSV file into a Pandas DataFrame.

#### Clean the data
Remove rows/columns, handle missing values, and fix data types.

#### Prepare the data
Derived columns and data shaping.

#### Analyze the data
Grouping, aggregating, and modeling.

#### Visualize the data
Create a minimum of four high-quality visualizations.

### 4. Documentation
Use Markdown, Raw, and Code cells to thoroughly document the process and thought logic.

### 5. Additional Requirements
Create a Jupyter Notebook.
Create a minimum of four visualizations. 
Identify the Python modules used in your Notebook. 

---

To generate the final report, run the following command in the terminal (assumes you have installed Jupyter and nbconvert):

```bash
jupyter nbconvert --to html christian_bongiorno_polling.ipynb
```

This will generate an HTML report from the Jupyter Notebook, which you can open in a web browser to view the final report.

## 📚 References

- **Textbook**: McCoy, Scott. *Murach's Python for Data Science (2nd Edition)*. Kindle Edition.