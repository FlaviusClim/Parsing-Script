# Script for parsing CSV file and return specific data

## Description

This Python script is designed to parse through CSV files 
containing signal data and extract specific information 
based on user input. It provides a convenient way 
to search for signals within the CSV file and 
save the parsed results to an Excel file for further analysis.

## Features

1. User Input: Users can specify the signals they want to search for within the CSV file.
2. CSV Parsing: The script reads the CSV file, skips unnecessary rows, and extracts relevant signal data into a pandas DataFrame.
3. Signal Search: It searches for specified signals within the DataFrame and identifies unique rows based on differences in specific columns.
4. Excel Export: Parsed results are saved to an Excel file, with each signal having its own sheet.

## Getting Started

### Dependencies

* You need to have an OS like Windows, Linux or MacOS
* You also need a functional IDE, preferably PyCharm
* You will need PANDAS, OPENPYXL and OS libraries

### How to run 

Install the required Python packages:

```pip install pandas openpyxl```

Place the CSV file in the same directory as the script.
Run the script: 

```python script_name.py```

Follow the on-screen instructions to input the signals.<br />
Parsed results will be saved in an Excel file 
named "Parsing_results.xlsx" in the same directory.

### Usage

* Input Signals: 
  * Run the script and provide the number and names of signals you want to search for.
    ```
    Insert the correct names of the signals 
    ```
  * In the next version of the script, Specific Error Messages will appear if name of signals are not correct
  * CSV File: 
    * Ensure the CSV file containing signal data is named "file.csv" and located in the same directory as the script.
    * CSV file must have same header as in the script. Although, you have to modify the header and other sections.
    ```
      Adjust the input CSV file name as you need
      ```
* Results: 
  * Parsed results for each signal will be displayed and saved to an Excel file named "Parsing_results.xlsx".
  * Again, you have to pay attention here because the script will overwrite the output file.
    ```
    Modify the output file name as you need like "Parsing_reuslts2.xlsx"
    ```

## Help

For any problems:
```
Close the script and re-run
```

## Authors

Contributors names and contact info

Flavius Clim
https://github.com/FlaviusClim

## Acknowledgments

Inspiration, code snippets, etc.
* [os.path.exists-tutorial](https://bobbyhadz.com/blog/python-input-file-path)
* [check-if-file-exists](https://www.learndatasci.com/solutions/python-check-if-files-exist/)
* [read-write-pandas](https://realpython.com/pandas-read-write-files/#write-files)
* [also-pandas](https://www.geeksforgeeks.org/how-to-read-text-files-with-pandas/)
* [curs-gratuit-python](https://www.youtube.com/watch?v=vrKiJWOeNyI&list=PLUVWXwPeA4CxcA2o1lCBGb2elaglSVRQ2&ab_channel=MariusCiurea)