# Red Light Camera Data Explorer

## Overview
This project is a C++ console-based data analysis tool designed to explore red-light camera violation data from the City of Chicago. The goal of this project was to practice working with real-world datasets by parsing, validating, and analyzing structured data.

Users can interactively explore traffic violations by filtering data based on neighborhood and month. This makes it easier to identify trends and patterns in the dataset.

## Features
- Parses and processes CSV datasets of red-light camera violations
- Structured **CameraRecord** data model for organizing data
- Menu-driven CLI interface for user interaction
- Filter data by neighborhood and month
- Strong input validation to handle incorrect inputs
- Displays summarized results for analysis

## Tech Stack
- **Language:** C++
- **Concepts:** Object-Oriented Programming, file I/O, data validation
- **Tools:** GCC, Command Line Interface
- **Data Source:** City of Chicago Open Data

## How It Works
1. The program reads and parses a CSV dataset
2. Each record is stored in a structured CameraRecord object
3. Users interact with a menu to query the dataset
4. The system filters and displays relevant results

## Challenges
- Handling inconsistent or missing data in CSV files
- Debugging parsing errors
- Designing flexible data structures
- Preventing crashes from invalid user input

## Future Improvements
- Add graphical visualization (charts)
- Build a web-based interface
- Optimize performance for larger datasets
