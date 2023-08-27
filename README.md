# FlightGrapher: City Connection Explorer

Welcome to the FlightGrapher project! This C++ program implements a flight route graph that allows you to explore connections between cities. It reads data from `city.name` and `flight.txt` files to provide route information and search functionality based on the number of connections.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)
- [Sample Input/Output](#sample-inputoutput)
- [Compile and Run](#compile-and-run)

## Prerequisites

To compile and run this program, you need to have the following:

- C++ compiler (GCC or Clang)
- `city.name` file containing the names of cities
- `flight.txt` file containing flight route information

## Usage

1. Clone the repository or download the source code files.
2. Place the `city.name` and `flight.txt` files in the same directory as the source code files.
3. Open a terminal or command prompt and navigate to the project directory.
4. Compile the code using the following command:

   ```shell
   g++ main.cpp -o flight

File Descriptions
main.cpp: The main C++ source code file that implements the flight route graph and provides search functionality.
city.name: A text file containing the names of cities, with each city name on a new line.
flight.txt: A text file containing flight route information, with each route on a new line in the format "sourceCity destinationCity".

Sample Input/Output
Here is an example of how the program can be used:
Please choose the type of question:
1: From city 'A' to city 'B' with less than x connections?
2: Route with the smallest number of connections from city 'A' to city 'D' through city 'B' and 'C'?
> 1

Please enter the city A: Moscow
Please enter the city B: London
Number of connections: 2

The route with the smallest number of connections from Moscow to London with less than 2 connections is:
Moscow -> Seoul -> Tokyo -> Hong Kong -> London
Total connections: 3

