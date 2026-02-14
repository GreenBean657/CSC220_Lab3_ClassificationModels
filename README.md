##  Lab 3: Classification Models
### CSC220
#### By Nathaniel Cruz

###### Description
Lab 3 for Neumont University, CSC220.
Predict the income dataset using various models.

###### Initialization

Create a new venv (Requires Python 3.12)
```commandline
python3 -m venv .venv
source .venv/bin/activate
```
Install required packages
```commandline
python -m pip install --upgrade pip
pip install -r requirements.txt
```

###### Execution
Run the main script
```commandline
jupyter notebook
```

Cache is stored in  
```commandline
mlp_time.txt
rf_best_params.txt
```
Please **DO NOT** delete these files.

### Notice:
Under Part 5, flag_perform_deep_search is flipped off to prevent a computationally expensive search.
To enable searching (may take hours), set flag_perform_deep_search to True in the notebook.