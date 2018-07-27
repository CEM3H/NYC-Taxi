# NYC Taxi trip prediction
This is my Capstone project for "Machine learning and Data analsis" Specialization at Coursera. 
The project is based on data from NYC Trip & Limousine Comission (TLC). Data represented by montly informaton of taxi trips in New York 
and contains GPS coordinates and time of pickups and drop-offs, fare amounts, number of passengers and other information. Full data 
decription you can find here: http://www.nyc.gov/html/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf.

The data itself could be found here: http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml.

## Project details
This project involves analysis of data of first six months of 2016 due to moderating computing power of my laptop, but initially 
it was designed to analyse as much data as needed. 
The purpose of the project is to build model (models) to predict amount of trips in NYC by regions. These regions were artificially
computed by dividing the big rectangle around NYC by 2500 equal-sized smaller rectangles. 

There will be ~7 Jupyter Notebooks providing step-by-step data analysis: collecting data, aggregation, visualisation and building prediction
models using regressions and ARIMA models. 
When it finished there will be some user-friendly interface to consume this predictions (I don't know exactly how it will look like yet).

Note: the structure of raw data was changed after June 2016 - instead of recording GPS coordinates they started to record zone IDs. This 
significantly complicates usage of this project's approach to identifying zones.
There are also shapefile and lookup table of NYC regions and boroughs on this page:
http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml

### Disclaimer
The project is not finished yet and there may be some comments in Russian and some simplifications, skipped parts and contractions 
but I will fix these things - eventually.
