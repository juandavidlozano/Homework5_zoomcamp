## Week 5 Homework 



### Question 1: 

**Install Spark and PySpark** 

- Install Spark
- Run PySpark
- Create a local spark session
- Execute spark.version.

What's the output?

from the picture we can see the answer is

'3.3.2'

<img src="https://github.com/juandavidlozano/Homework5_zoomcamp/blob/main/homework5.1.jpg" alt="Answer 1" width="1000" height="500">

### Question 2: 

**FHV October 2019**

Read the October 2019 FHV into a Spark Dataframe with a schema as we did in the lessons.

Repartition the Dataframe to 6 partitions and save it to parquet.

What is the average size of the Parquet (ending with .parquet extension) Files that were created (in MB)? Select the answer which most closely matches.

- 1MB
- 6MB
- 25MB
- 87MB


Answer
- 6MB

### Question 3: 

**Count records** 

How many taxi trips were there on the 15th of October?

Consider only trips that started on the 15th of October.

- 108,164
- 12,856
- 452,470
- 62,610

from the picture we can see the answer is

- 62,610

<img src="https://github.com/juandavidlozano/Homework5_zoomcamp/blob/main/homework5.2.jpg" alt="Answer 1" width="1000" height="500">

### Question 4: 

**Longest trip for each day** 

What is the length of the longest trip in the dataset in hours?

- 631,152.50 Hours
- 243.44 Hours
- 7.68 Hours
- 3.32 Hours

from the picture we can see the answer is

- 631,152.50 Hours

<img src="https://github.com/juandavidlozano/Homework5_zoomcamp/blob/main/homework5.3.jpg" alt="Answer 1" width="1000" height="500">

### Question 5: 

**User Interface**

Spark’s User Interface which shows the application's dashboard runs on which local port?

- 80
- 443
- 4040
- 8080

  Answer 4040

### Question 6: 

**Least frequent pickup location zone**

Load the zone lookup data into a temp view in Spark</br>
[Zone Data](https://github.com/DataTalksClub/nyc-tlc-data/releases/download/misc/taxi_zone_lookup.csv)

Using the zone lookup data and the FHV October 2019 data, what is the name of the LEAST frequent pickup location Zone?</br>

- East Chelsea
- Jamaica Bay
- Union Sq
- Crown Heights North

from the picture we can see the answer is

- Jamaica Bay

<img src="https://github.com/juandavidlozano/Homework5_zoomcamp/blob/main/homework5.4.jpg" alt="Answer 1" width="1000" height="500">
