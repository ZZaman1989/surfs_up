# Surfs Up

## Project Summary and Background
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## What You're Creating

> This new assignment consists of two technical analysis deliverables and a written report. You will submit the following:

1. ***Deliverable 1***: Determine the Summary Statistics for June
2. ***Deliverable 2***: Determine the Summary Statistics for December
3. ***Deliverable 3***: A written report for the statistical analysis [`README.md`]. 


## Deliverable 1:  Determine the Summary Statistics for June
Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

### Deliverable Requirements:
You will earn a perfect score for Deliverable 1 by completing all requirements below:

1. A working query is written to retrieve the June temperatures from the `date` column of the `Measurement` table.
2. The temperatures are added to a list.
3. ​The list of temperatures is converted to a Pandas DataFrame.
4. Summary statistics are generated for the DataFrame.

 
### Results with detail analysis:

1. **A working query is written to retrieve the June temperatures from the `date` column of the `Measurement` table.**

> Image with `Jupyter Notebook`

![name-of-you-image](https://github.com/ZZaman1989/surfs_up/blob/main/Resources/Deliverable%201.1.png)

2. **The temperatures are added to a list.**

> Image with `Jupyter Notebook`

![name-of-you-image](https://github.com/ZZaman1989/surfs_up/blob/main/Resources/Deliverable%201.2.png)

3. **​The list of temperatures is converted to a Pandas DataFrame.**

> Image with `Jupyter Notebook`

![name-of-you-image](https://github.com/ZZaman1989/surfs_up/blob/main/Resources/Deliverable%201.3.png)


4. **​Summary statistics are generated for the DataFrame.**

> Image with `Jupyter Notebook`

![name-of-you-image](https://github.com/ZZaman1989/surfs_up/blob/main/Resources/Deliverable%201.4.png)


### Deliverable 2: Determine the Summary Statistics for December.
Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of December. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

### Deliverable Requirements:
You will earn a perfect score for Deliverable 2 by completing all requirements below:

1. A working query is written to retrieve the December temperatures from the `date` column of the `Measurement` table.
2. The temperatures are added to a list.
3. ​The list of temperatures is converted to a Pandas DataFrame.
4. Summary statistics are generated for the DataFrame

### Results with detail analysis:

1. **A working query is written to retrieve the December temperatures from the `date` column of the `Measurement` table.**

> Image with `Jupyter Notebook`

![name-of-you-image](https://github.com/ZZaman1989/surfs_up/blob/main/Resources/Deliverable%202.1.png)


2. **The temperatures are added to a list.**

> Image with `Jupyter Notebook`

![name-of-you-image](https://github.com/ZZaman1989/surfs_up/blob/main/Resources/Deliverable%202.2.png)


3. **​The list of temperatures is converted to a Pandas DataFrame.**

> Image with `Jupyter Notebook`

![name-of-you-image](https://github.com/ZZaman1989/surfs_up/blob/main/Resources/Deliverable%202.3.png)


4. **​Summary statistics are generated for the DataFrame.**

> Image with `Jupyter Notebook`

![name-of-you-image](https://github.com/ZZaman1989/surfs_up/blob/main/Resources/Deliverable%202.4.png)



## Deliverable 3: A written report for the statistical analysis
For this part of the Challenge, write a report that describes the key differences in weather between June and December and two recommendations for further analysis.

### The analysis should contain the following:

1. **Overview of the analysis:** W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
> Below our Analysis that what we found:

2. **Results:** 

**June Temps - Analysis and Result**
* Count of 1700 
* Mean of 74.94 
* Std of 3.26 
* Min of 64.00 
* 25% of 73.00 
* 50% of 75.00
* 75% of 77.00
* Max of 85.00

    -   Junes avg temp is 75 degrees.
    -   Std is approx 3.
    -   First and Third quarter are most appropriate conditions.


**December Temps - Analysis and Result**
* Count of 1517 
* Mean of 71.04 
* Std of 3.75
* Min of 56.00 
* 25% of 69.00 
* 50% of 71.00
* 75% of 74.00
* Max of 83.00

    -   Avg temp is 71 degrees.
    -   Std is approx 4.
    -   The max temprature is only two degrees lower than June.


3. **Summary:** It would be a good idea to open up shop due to the perfect weather condiditions.  The difference between June and December weather is immaterial. In addition, two additional queries to perform to gather more weather data are rain and wind.


