# DataSci
## About
This project attempts to find a relation between diet and mental health. International data sets are used to calculate the correlation between dier and depression. It also attempts to use other known factors impacting mental health to compare with diet. This is done using Jupyter notebooks available in the Notebooks directory. Instructions for replication should be available in the nootbooks.<br /> 
## Presentation of Work
https://docs.google.com/presentation/d/1X4Ojl91RiWX5I9znxRgBedXdrkMLA_ymOeDivT_dNfw/edit?usp=sharing
## Authors
- Hoang Bui
- Samuel Catherasoo
- Michael Fan
- Derek Shao
- Souheil Yazji

# Data Sets

## Raw Data

The following links were used to produce the raw data. 

* https://apps.who.int/nha/database/Select/Indicators/en<br />
* http://www.fao.org/faostat/en/#data<br />
* https://data.worldbank.org/indicator/NY.GDP.MKTP.CD<br />
* https://ourworldindata.org/mental-health

Raw data files are also available in the "Raw Data" directory.
## Clean Data
The processed data can be found in the "Processed Data" directory.

# Dependencies
Pandas is used for data set processing: <br />
`import pandas as pd` <br /><br />
Pycountry is used for extracting the ISO code from country names, this helps merge differing country names from different datasets:<br />
`import pycountry`<br /><br />
Plotly is used for data visualization:<br />
`import plotly.express as px`<br /><br />
Seasborn is used as a correlation data visualization library:<br />
`import seaborn`<br /><br />

# Process

Feel free to either clone this repository locally or to save the notebooks. This should ideally be in a Jupyter environment, but it is also possible to use other platforms such as Google Collaboration or Visual Studio Code. The environment should have the dependencies listed above. The repository also includes the data files, both raw and processed, used for the project. The Notebooks avialable are divided in to two directories, "Data Analysis" and "Data Preperation".


1. We start by generating all of the raw data using the sources provided in the "Raw Data" section. It's also possible to use the raw data files available in our "Raw Data" directory.

2. The notebooks contain in-line instructions to walk the user through the notebook process. Start by using the Data Preperation notebooks to prepare the processed data. The results produced should be identical to the results in the "Processed Data" directory. 

3. Save the processed data into the appropriate directory. Note: the "Data Analysis" notebooks rely on the file structure of this repository to find the appropriate files. By saving the processed data elsewhere or modifying the file structure it is likely that the code will need to be altered. 

4. Run the "Data Analysis" notebooks with the appropriate processed data files. This should generate the same results reported in our project. 