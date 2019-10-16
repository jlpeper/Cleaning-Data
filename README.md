# Cleaning-Data
Extracts important information from messy Cary 5000 data. 
Python Code: DateTime, NumPy, Pandas, and regular expressions.


The provided code can be used to extract important data (scan name, datetime of measurements, absorbance, and wavelength) from Cary 5000 or Cary 60 csv data formats.

This code demonstrates use of regular expressions, datetime, pandas, and numpy libraries.

Code break down:
1. Import necessary packages.
2. Open Cary data (cry_test_data.csv) and read in each line.
3. Extract the scane name scan from the first line in of imported data (raw_data).Store scan names in list, "names".
4. Extract the wavelength and all absorbance values for each scan. Store values in dictionary with wavelength for keys and absorbance for values.
5. Extract collection time and date as strings of each scan from the raw_data. Convert the strings to datetime objects and store in list "collection_datetime". Determine the difference (in minutes) between the datetime object of each scan, store in list "delta_time".






