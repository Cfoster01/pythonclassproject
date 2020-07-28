# pythonclassproject
### Christina Foster's Project for May 2020 Python Class
This project takes a look at a couple of fabricated data sets that accurately reflect the types of data sets I use in everyday work. It analyzes the data and produces insights around how Training feedback correlates to key business metrics.

### Technical Summary
- Python 3.8
- Jupyter Notebook

### Installation and Running
1. 'git clone https://github.com/Cfoster01/pythonclassproject.git'
2. If not already installed, install pandas, bokeh, scipy, and Jupyter Notebook using pip with the following commands:
    - `pip install pandas`
    - `pip install bokeh`
    - `pip install scipy`
    - `pip install notebook`
3. Run Jupyter Notebooks from terminal with the command:
    - `jupyter notebook`
4. Open the pythonclassproject-master/TrainingAnalysisProject.ipynb notebook
5. Click **Cell** and **Run All** to run the entire notebook

### Project Requirements
- The project is on GitHub with at least 5 commits and includes this README file as well as comments within the Jupyter Notebook.
- Imported two CSV files into a data frame, then combined into new data frame (Line 2 - 8)
- Analyzed text and displayed information about it, including:
    - Data associated with those who responded 'Yes' and 'No' to a survey question (Line 15 - 27)
    - Frequency of qualitative data phrases from an open response survey question (Line 28 - 29)
- Defined the function `table_converter` which creates x and y axis lists for Bokeh bar graphs, making it easier to reproduce for additional data (Line 41)
- Added in Bokeh data visualizations to make trends easier to see and understand
    - Scatter Plots (Line 37 - 39)
    - Bar Graph (Line 43)

### Additional Project Features
- Used Jupyter Notebook
- Used external libraries: Pandas, Bokeh, & SciPy
- Ran in-depth statistical significance tests using SciPy and displayed outputs that could be used for decision making (Line 30 - 36)