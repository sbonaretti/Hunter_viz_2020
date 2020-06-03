# John Hunter - Excellence in Plotting Context 2020

## Dashboard live and on binder 
Coming soon!

## Run the dashboard locally 
In terminal:
- Install voilà and jupyter-flex:  
  ```
  pip install voila
  pip install jupyter-flex
  ```
- Create the dashboard:
  ```
  voila --template=flex open_literature_flex.ipynb 
  ```
Note: If using JupyterLab, might need to restart
  
## How to reuse the code for your own dataset
- Fill out `data_template.csv` with your own data. Information about the data fields are in the file itself  
- In `open_literature_flex.ipynb`, under `Load the data`:
  - Change file name to your own `.csv` file name  
  - Comment out `zenodo_url = "https://zenodo.org/record/3872040/files/"`
  - Comment out `wget.download(zenodo_url + file_name, "./" + file_name) # input, output`
- Make sure your `.csv` file is in the same folder as your notebook
