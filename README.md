# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.

## Importing Anaconda/Miniconda environment using .yml file
- Use env.yml provided to import the required environment where python=3.7
- Use the following command > conda env create -n mle-dev --file env.yml

## To excute the script
- Add the fetch_housing_data() - Code line to the code
- housing = load_housing_data - Has missing brackets at the end add them
- python nonstandardcode.py

## To format the code
- Install black, isort, flake8 in your working environment
- Run flake8 <file_name.py> to check errors