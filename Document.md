# Grootan Coding Assignment

Problem Statement:
------------------
  Create a web application with an option to upload a CSV file of 1 lakh or more records, 
where the application should read the records, process it, and push to the database table.
The CSV file will have a header row that denotes the database table column names and rows 
which represent the values of the database table.
After the upload of the CSV file, only the database table should be created dynamically 
based on the header names of the CSV file and the insert of row values should be carried 
out later.
In case if there are any header named as “password”, the value should be encrypted 
dynamically and saved in the database.
Share the final coding via GitHub

# Massive CSV data to Database Import Software :
```bash 
Dynamic CSV importing to A database (here MySql) is a short process where we upload a CSV file and the PHP commits it to the MY Sql database 
fetching every data accurately.
> I have utilized PHP language for the back end integration of my information base . 
> I utilized JS for more powerfully dependent on the header names of the CSV record and the addition of column esteems ought to be completed later. 
> I have utilized html language for UI/UX design along with a little bit of CC Styling. 
> Sql is used as the mjor database for storing the fetched and retrieved data 
The requrements and the processing steps with the snaps are described below in the same document.
```



Table of Contents
-----------------
  * [Requirements](#requirements)
  * [Processing](#processing)
  
   
Requirements
------------
CSV Import requires the following to run:
  * [VS Code or Any Other IDE that supports JS,PHP,HTML][vscode]
  * [Apache Server][apache] 
  * [MySQL Community Server][mysql]  
  * [XAMPP Can be preferred as it contains both Apache and Mysql Servers] [xampp]


Processing:
----------------------
**1) Read/ Write Processing Of CSV :**

![Upload error](https://github.com/Dhivira-119/R.Dhivya_Grootan_CA/blob/main/CSV%20Importing.png)

```bash 
The CSV file which contains 1 Lakh employee data is imported to the My Sql Dtabase using PHP Back end.. Above is the code snap of the csv and initial code
```

**2) Database Data Retrieval :**

![Upload error](https://github.com/Dhivira-119/R.Dhivya_Grootan_CA/blob/main/Database%20Data.png)

```bash 
The data from the CSV file is imported to the Database dynamically with the help of the PhP and the above is the snap of the CSV data in the database
```

**3) Encryption Algorithm :**

![Upload error](https://github.com/Dhivira-119/R.Dhivya_Grootan_CA/blob/main/Pass%20Encryption.png)

```bash 
We've used the MD5 hashing encryption to dynamically encrypt all the data in the password column
```
**4) Elapsed Time and Record Count :**

![Upload error](https://github.com/Dhivira-119/R.Dhivya_Grootan_CA/blob/main/Elapsed%20Time.png)

```bash 
Processing 1 lakh+ records in less than three minutes is the best dynamic functionality of my code and the record count can also be traced out
```
![Upload error](https://github.com/Dhivira-119/R.Dhivya_Grootan_CA/blob/main/recordcount.PNG)

```bash 
The record count can also be traced out after the import is completed
```

**5) Error Message**

![Upload error](https://github.com/Dhivira-119/R.Dhivya_Grootan_CA/blob/main/Iferror.png)
```bash 
 Dynamic Error detection
```

# Software Links:
VSCODE: https://code.visualstudio.com/download
XAMPP: https://www.apachefriends.org/index.html
