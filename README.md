# Data Analysis with Python: NumPy & Pandas

This repository consists of some of the assignments and hands-on practices that I have done by taking the [Data Analysis with Python: NumPy & Pandas Masterclass](https://www.udemy.com/course/python-pandas/) course on Udemy. 

The course covers NumPy & Pandas for Data Science, Data Analysis & Business Intelligence:
* Master the essentials of NumPy and Pandas
* Learn how to explore, transform, aggregate and join NumPy arrays and Pandas DataFrames
* Analyze and manipulate dates and times for time intelligence and time-series analysis
* Import and export flat files, Excel workbooks and SQL database tables using Pandas
* Visualize raw data using plot methods and common chart options like line charts, bar charts, scatter plots and histograms 

## The Maven MegaMart Course Project

_Act as a newly hired Data Analyst for **Maven MegaMart**, a multinational corporation that operates a chain of retail and grocery stores._

* Mid-Course Project - Maven Acquisition Target Data
* Final Project - Maven Acquisition Target Data

They recently received a sample of data from a new retailer they're looking to acquire, and they need you to identify and deliver key insights about their sales history. 

The assignment is to **analyze over 2 million transactions** by product, household, and store to get a better understanding of the retailer's main strengths. From there, we need to review the company's discount scheme to assess whether they can expect to attract customers without losing margin. 

#### Use Python to:
* Read in multiple flat files efficiently
* Join tables to prove a single source of information 
* Shape & aggregate sales data to calculate KPIs
* Visualize the data to communicate findings 

---

### Setup & Run Jupyter Notebooks in VS Code w/ Virtual Env & Kernels

I completed below setup instead of using Anaconda (course instruction):
* create a virtual environment
  ```
  python3 -m venv jupyter-env 
  ```
* activate the virtual env
  ```
  source jupyter-env/bin/activate
  ```
* Installation 

  ```
  pip install jupyterlab
  
  pip install ipykernel
  ```
  _Validate that the install has succeeded by running `jupyter-lab` from your command line. A new tab should open in your browser, with the JupyterLab application running._
  
  * install useful Python packages in this virtual env
  

  ```
  pip install numpy
  pip install pandas
  pip install openpyxl
  pip install matplotlib
  pip install seaborn
  ```
  
* register the new virtual env with Jupyter so that you can use it within JupyterLab

  ```
  python3 -m ipykernel install --user --name=‘maven-python‘ 
  ```
  
Now open an existing/create a new `.ipynb` file in VS Code and select the `maven-python` Kernel to use
