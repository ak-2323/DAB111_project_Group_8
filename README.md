# Project Title : Store the data in a database and display on the server

## Project Description :
In this project, we mainly focus on the displaying data using python. First, we find dataset from [Kaggle](https://www.kaggle.com/datasets). Here, we get unfiltered dataset as it contains missing values and unnecessary columns. In order to work with data, we first need to do data processing. Therefore, in `data_processing` folder we created one `.ipynb` file which contains code to handle missing values and drop unnecessary columns. At the end, it generate one clear and well-structured CSV file into `database` folder.

In the next step, we use that filtered CSV file to store data into database using code written in `build_db_fillin.py`. Here, saved our data into `titanic.db` file which generated in `website` folder. To perform this operation, we used some python libraries such as Pandas, Sqlite3 and Pathlib.

In the Last step, we created one `app.py` python file to run the server using `Flask` module. Also, with the html files stored in `templates` folder display data on the server. In `about.html` file we mention description regarding dataset like where we found it and what all column state for. With  the help of flask syntax and html structure we display our sample data in the tabular format. 

__Note :__ To run the project into your computer, first run this command `pip install -r requirements.txt` as it contains all necessary libraries required to run this project.

## Libraries Used in this Project
 - __Pandas :__ For data manipulation and analysis and present data in well-structure format.
 - __Sqlite3 :__ Store data into database 
 - __Pathlib :__ Retrieve path of each file
