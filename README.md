 # Data-Cleaning-Pipeline-ETL
 [Click here to see the dataset.](https://www.kaggle.com/datasets/stefanoleone992/filmtv-movies-dataset)
 ## Problem Statement
 The problem was to extract data from two csv files with the records of 40k plus rows from the azure datalake gen2 storage then combine those two files with the the SQL join to create a single table then perform some cleaning like removing null values, unnecessary columns and then transfer it to azure SQL database.
 ## The Json files
 The First Portfolio Project.json file contains information about the ADF pipeline, including the pipeline name, description, and the resources that make up the pipeline. The manifest.json file contains information about the dependencies and structure of the ARM template of the pipeline in Azure DataFactory.
## Workflow 
![Untitled Diagram drawio](https://user-images.githubusercontent.com/123824748/234919518-c43c67f1-4aa4-4b4e-bc80-f7d8bbcdb7e7.png)
## Pipeline Structure
![Capture](https://user-images.githubusercontent.com/123824748/234919863-8e0980e4-de84-4c0c-bb71-0045ae521037.PNG)
## Data at the Destination (SQL database)
![Capture2](https://user-images.githubusercontent.com/123824748/234920301-51f0faac-cd24-415a-8de9-4ed1713643d4.PNG)
