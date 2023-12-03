# CSV Parcer

## Overview

This console application validates email addresses from a CSV file, categorizing them as either valid or invalid based on a predefined rule. The project utilizes the CsvHelper library for CSV parsing.

## Features

- **File Validation:** Checks if the specified CSV file exists in the current directory.
- **CSV Parsing:** Reads the CSV file using CsvHelper and extracts email addresses.
- **Email Validation:** Determines if each email address is valid based on predefined rules.
- **Results Output:** Displays separate lists for valid and invalid email addresses.

## Prerequisites

- .NET 5.0 or later
- CsvHelper library (automatically installed via NuGet)

## Usage

1. Run the application.
2. Enter the name of the CSV file when prompted.
3. View the results showing valid and invalid email addresses.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Yousefh1/Technical-project.git

## Example
Enter the CSV file name:
sample_data.csv

File 'sample_data.csv' found at: /path/to/your/project/sample_data.csv

Valid Email Addresses:
test@gdcit.com
another_test@gdcit.com

Invalid Email Addresses:
test1@gmail.com
test2@hotmail.com
