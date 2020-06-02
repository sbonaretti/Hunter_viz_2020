# John Hunter - Excellence in Plotting Context 2020

Dashboard live and on binder soon 


## How to reuse the code for your own dataset
- Fill out `data_template.csv` with your own data. Information about the data fields are in the file itself  
- In `open_literature_flex.ipynb`, under `Load the data`:
  - Change file name to your own `.csv` file name  
  - Comment out `zenodo_url = "https://zenodo.org/record/3872040/files/"`
  - Comment out `wget.download(zenodo_url + file_name, "./" + file_name) # input, output`
  - Make sure your `.csv` file is in the same folder as your notebook
