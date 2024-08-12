# Coin-Change-Calculator-in-C
## Key Features

1. **Data Structures**:
   * **Structs**: Used for organizing currency data for each individual.
   * **Dynamic Arrays**: Implemented for flexible storage of records.
   * **File I/O**: Utilized for reading input data and writing output results.

2. **Currency Data Management**:
   * **Data Collection**: Functions to read and store currency data from an input file.
   * **Change Calculation**: Methods to calculate coin change for different denominations in multiple currencies (US, AUS, EUR).
   * **Data Display**: Functions to present the calculated change in a readable format.

3. **Modular Design**:
   * The program is structured with clear, modular code, making it easy to understand, extend, and maintain.
   * Separation of concerns is maintained with distinct functions for data input, processing, and output.

## Main Components

1. **InitializeRecords()**: Initializes the fields of an array of 'record' structures to default values.
2. **readFile()**: Reads data from the input file and stores it in the records array.
3. **SearchRecords()**: Searches for a given name in the records array.
4. **CalculateCents()**: Calculates the number of whole coins and remaining cents for a given amount.
5. **InputName()**: Handles user input for searching records by name.
6. **ConsoleMenu()**: Displays a menu for user interaction.
7. **WriteToFile()**: Writes the calculated change data to an output file.

## Usage

The program reads initial data from 'coins.txt', allows users to interact via a console menu to search for records and calculate change, and then writes the final results to 'change.csv'.
