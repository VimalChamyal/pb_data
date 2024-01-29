# PB Data analysis assignment

In this assignment I've worked on a DataOps teams' dataset. My objective was to come up with insights from the data that can help the client (TL) understand the production and the performance of his/her team.


# Tools used & my approach

MS Excel, Python, PowerBI, Google Colab
 
1. Loaded the 'Data.csv' file on Excel to get acquainted with the data.
2. Imported the csv file in google colab to understand the data better by performing EDA using python. Was able to find few key metrics on which I could focus while working on data visualization using Power BI. The notebook is named 'pdata.ipynb'. Check it above or click <a href="https://github.com/VimalChamyal/pb_data/blob/main/pdata.ipynb">here</a>.
3. Performed data transformation & loaded the dataset in Power BI for the interactive visualization of my key findings. The file name is 'pbdata.pbix'. Check it above or click <a href="https://github.com/VimalChamyal/pb_data/blob/main/pbdata.pbix">here</a>.
4. Tried to make the dashboards appealing.

Please find 'Data.csv', 'pdata.ipynb' & 'pbdata.pbix' files above for reference.
 

# SECTION I. OVERVIEW OF THE DATASET & BASIC EDA
Please refer the file 'pdata.ipynb'. Check it above or click  <a href="https://github.com/VimalChamyal/pb_data/blob/main/pdata.ipynb">here</a>. I will be using the screenshots from this file

## A. Descriptive statistics of the numerical columns (Time taken to Complete & Benchmark Points) in the dataset.

The statistics shown below provide a quick overview of the distribution of the 2 numerical columns in the dataset, helping us to understand the central tendency, dispersion, and shape of the data.

<img width="332" alt="image" src="https://github.com/VimalChamyal/pb_data/assets/101229988/568c9e8b-ec46-4596-9f52-4a2923e16582">

Here's what each statistic means:

1. count: The number of non-null observations in the column.
2. mean: The average value of the observations.
3. std: The standard deviation, which measures the dispersion or spread of the values around the mean.
4. min: The minimum value in the column.
5. 25% (Q1): The value below which 25% of the observations fall.
6. 50% (Q2): The median, the value below which 50% of the observations fall.
7. 75% (Q3): The value below which 75% of the observations fall.
8. max: The maximum value in the column.

An overview of the above statistics can be seen below (in the form of charts):

![image](https://github.com/VimalChamyal/pb_data/assets/101229988/fd41f653-1694-44cd-911b-7a4a11fdb6d8)
![image](https://github.com/VimalChamyal/pb_data/assets/101229988/c648eb69-1903-4a6d-9624-866179e5e5f0)


## B. Unique values in each columns.

Checking for unique values in each columns of the data. Getting an idea, which columns can be continous & which can be categorical.

<img width="346" alt="image" src="https://github.com/VimalChamyal/pb_data/assets/101229988/66c1679a-6302-4c14-9142-2cef27a30296">

## C. Distribution of the columns

Checking the distribution of values in the important columns.

![image](https://github.com/VimalChamyal/pb_data/assets/101229988/131ada58-bec0-4874-aa3b-a996542a2f90)
![image](https://github.com/VimalChamyal/pb_data/assets/101229988/11d2c122-9ceb-45ab-a321-46a688b02340)
![image](https://github.com/VimalChamyal/pb_data/assets/101229988/e1fbd8de-5709-4d9d-899b-842263f7a39f)

# SECTION II. DATA ANALYSIS & VISUALIZATION
Please refer the file 'pbdata.pbix'. Check it above or click <a href="https://github.com/VimalChamyal/pb_data/blob/main/pbdata.pbix">here</a>. I will be using the screenshots from this file

## A. Summarized analysis/view
We'll be able to see the important metrics like Benchmark Points & Time taken to complete (in mins) wrt to Profile IDs. One can make use of the filters Research Group, Workflow Type, Workflow Status, Workflow Process in order to get the indepth analysis. PFB a sample view with 'MUM - D - NC/NR' filter applied in the Research Group & 'Co Early Stage - New Company' filter applied in the Workflow Type.  

<img width="629" alt="image" src="https://github.com/VimalChamyal/pb_data/assets/101229988/8643a60c-5969-4f5a-8b96-d039a52b036e">






