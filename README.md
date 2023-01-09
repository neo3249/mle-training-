# mle-training
Training modules in Core Data Science

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

## To run the script
- Firstly open the Ubuntu/conda terminal 
- Now, activate the conda virtual environment namely mle-dev 
  
  - `conda activate mle-dev`

- Install all the related dependencies as per environment.yml file using pip3.
  - `pip3 install {{package_name}}`

- Run, python code.py in the same terminal. 
  - `python3 code.py`
