# aaa-2024-group-5
This is the repository of group 5 (Algorithm Amigos Anonymos) for the AAA Group Project for the course Advanced Analytics and Application in the summer term of 2024. 

## Prerequisites 

Please ensure you have Python installed. 

## Installation

1. Clone this repository to have it available on your machine.

2. Download the following files as they could not be added to the repository due to their size:
   
   1. The taxi trip dataset for 2019.  the notebook called 01_01_data.cleaning.ipynb. It is not used in any other notebooks. You can retrieve the data here:
      https://data.cityofchicago.org/Transportation/Taxi-Trips-2019/h4cq-z3dy/data .
      The filter for the 2019 timeframe should already be pre-selected.
   2. The land use data from the city of Chicago.You can retrieve the data here:
      https://datahub.cmap.illinois.gov/datasets/ef5f2092556c409d94d119bd821ec6da_2/explore?filter s=eyJGSVJTVF9DT1VOVFkiOlsiMDMxIl19&location=41.827915%2C-  88.109641%2C8.95

3. Rename the files.

   1. Taxi Trip Dataset: taxi_main copy.csv
   2. Land Use Dataset: land_use.geojson

4. Add these files to the "data" folder.

5. In order to be able to run the Jupyter Notebook files in this repository, you must install the required Python libraries. These dependencies are listed in the requirements.txt file. Run the requirements.txt file first to install all required libraries, for example by running the following command:  pip install -r requirements.txt (requires pip installation)
Alternatively, you can manually install the libraries listed in the requirements.txt file/in each notebook. 

## Notebook Execution Order

The right order to run the notebooks is indicated by the number in the title, e.g. 01_data_cleaning.ipynb and so on.









