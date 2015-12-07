# Data Pipeline Discovery

### Background

This project compares different methods for managing a report data pipeline.  To compare different solutions, the classic Northwind database was chosen.  It provides a simple schema that is well understood.  In addition, there are existing databases with sample data.  The following is a list of the solutions being compared:

- SQLite (baseline)
- Apache Drill (JSON + file system)

Jupyter Notebook is used to run code and visualize the comparisons -> http://jupyter.org/

### Getting everything installed

**Python 2.7 with Virtualenv**

Make sure you have a working Python 2.7 environment.  On OS X, you should install python through homebrew -> http://docs.python-guide.org/en/latest/starting/install/osx/

Install and configure a Virtualenv -> http://docs.python-guide.org/en/latest/dev/virtualenvs/#virtualenvironments-ref

Install using pip

`pip install virtualenv`

Create a virtual environment (this can live in your project folder; filtered out by .gitignore)

`virtualenv env`

Activate Virtual environment

`source env/bin/activate`

Install required 3rd party libraries

`pip install -r requirements.txt`


**Start Jupyter notebook server**

`jupyter notebook`

Open the appropriate notebook in the 'notebooks' folder.
