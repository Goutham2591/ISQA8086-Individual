# Data Entry Analysis

### Task 1: List the Problems in the provided data

###### For this Data Entry Analysis, we were provided three excel files which were a part of a study of distribution of two types of Zoo Planktons during day and night through years

###### Certain errors that I found from the data as follows:
  
  * The Column Headers are not incosistent accross the files.
  * There are few missing data in the files, which would make the data inefficient to gather results.
  * There are no details of colour coded data accross the files.
  * Time is not mentioned in any of the files which means that the data might have been entered twice at the same time.
  * There is no clear details about the temperature recorded and units in which it was recorded in.
  * what does the column 'z' mean in the pond2010 file. Is it the depth or any unit
  * Units in much of the columns are not mentioned
  * The graph plotted in both spreadsheets are for different columns. And the x and y values are not mentioned for these graphs.
  * The averages are calculated, but no correct description was given in the file.
 
### Task 2: Suggesting a new system for the organisation:

  * The suggested File Name accross the data collection would be ZooPlanktonStudy V.0 with a changing version number like V.1 everytime they record the data.
  * The table has headers that would have consistent column header.
  * I have eliminated two columns of species ( Cuni and chippo ), instead I created a column named "Species".
  * The units for every data entered is given in the header.
  * The graphs can be drawn for the both species separately considering the depth, density or colony size.
  * A Timestamp field is given so that the data can be consistent and any redundancy can be avoided.
  
  | Timestamp | Depth (Meters) | Temperature (Farenheit or celcius) | Species Name | Colony Size (Millimeters) | Density (Cubic Centimeters or milliliters) | Chlorophyll a |
|:---------:|:--------------:|:----------------------------------:|:------------:|:-------------------------:|:------------------------------------------:|:-------------:|
|           |                |                                    |              |                           |                                            |               |
