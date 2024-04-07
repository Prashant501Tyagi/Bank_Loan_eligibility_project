Loan Approval/Eligibility Problem
This dataset concerns loan data. When a customer applies for
a loan at our company, we use statistical models to
determine whether or not to grant the loan based on the
likelihood of the loan being repaid. The factors involved in
determining this likelihood are complex, and extensive
statistical analysis and modelling are required to predict the
outcome for each individual case. You must implement a
model that predicts if a loan should be granted to an
individual based on the data provided
The dataset used is an anonymized synthetic data that was
generated specifically for use in this project. The data is
designed to exhibit similar characteristics to genuine loan
data.

Description
In this dataset, you must explore and cleanse a dataset
consisting of over 1,00,000 loan records to determine the
best way to predict whether a loan applicant should be
granted a loan or not. You must then build a machine
learning model that returns the unique customer ID and a
loan status label that indicates whether the loan should be
given to that individual or not.

Data filesThe dataset consists of the
following fields:
• Loan ID: A unique Identifier for the loan information.
• Customer ID: A unique identifier for the customer.
Customers may have more than one loan.
• Loan Status: A categorical variable indicating if the
loan was given to this customer
• Current Loan Amount: This is the loan amount
that was either completely paid off, or the amount that
was defaulted. This data is for previous loan
• Term: A categorical variable indicating if it is a short
term or long term loan.
• Credit Score: A value between 0 and 800 indicating
the riskiness of the borrower’s credit history.
• Years in current job: A categorical variable indicating
how many years the customer has been in their current job.
• Home Ownership: Categorical variable indicating home
ownership. Values are "Rent", "Home Mortgage", and
"Own". If the value is OWN, then the customer is a home
owner with no mortgage
•Annual Income: The customer's annual income
• Purpose: A description of the purpose of the loan.




# Execution Instructions



# Python version 3.8.10

To create a virtual environment and install requirements in Python 3.8.10 on different operating systems, follow the instructions below:

### For Windows:

Open the Command Prompt by pressing Win + R, typing "cmd", and pressing Enter.

Change the directory to the desired location for your project:

`cd C:\path\to\project`

Create a new virtual environment using the venv module:

`python -m venv myenv`

Activate the virtual environment:

`myenv\Scripts\activate`

Install the project requirements using pip:

`pip install -r requirements.txt`


### For Linux/Mac:

Open a terminal.

Change the directory to the desired location for your project:

`cd /path/to/project`

Create a new virtual environment using the venv module:

`python3 -m venv myenv`

Activate the virtual environment:

`source myenv/bin/activate`

Install the project requirements using pip:

`pip install -r requirements.txt`

These instructions assume you have Python 3.8.10 installed and added to your system's PATH variable.


## Execution Instructions if Multiple Python Versions Installed


If you have multiple Python versions installed on your system , you can use the Python Launcher to create a virtual environment with Python 3.8.10, you can specify the version using the -p or --python flag. Follow the instructions below:

### For Windows:

Open the Command Prompt by pressing Win + R, typing "cmd", and pressing Enter.

Change the directory to the desired location for your project:

`cd C:\path\to\project`

Create a new virtual environment using the Python Launcher:

`py -3.8 -m venv myenv`

Note: Replace myenv with your desired virtual environment name.

Activate the virtual environment:

`myenv\Scripts\activate`

Install the project requirements using pip:

`pip install -r requirements.txt`


For Linux/Mac:

Open a terminal.

Change the directory to the desired location for your project:

`cd /path/to/project`

Create a new virtual environment using the Python Launcher:

`python3.8 -m venv myenv`
Note: Replace myenv with your desired virtual environment name.

Activate the virtual environment:

`source myenv/bin/activate`
Install the project requirements using pip:

`pip install -r requirements.txt`


By specifying the version using py -3.8 or python3.8, you can ensure that the virtual environment is created using Python 3.8.10 specifically, even if you have other Python versions installed.






