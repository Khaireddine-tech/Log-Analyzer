# CMP2003 Data Structures and Algorithms (C++) - Term Project: Log Analyzer

## Project Overview

### Introduction
This project involves creating a C++ console application for analyzing web server logs. The program reads a text file containing log entries, processes the data, and identifies the top 10 most visited web pages. The implementation includes two different approaches for storing and managing data: a custom hash table and `std::unordered_map`. The goal is to compare the efficiency of these two implementations.

## 1. Main Requirements

### 1.1 Log Format
The log file comprises entries with the following format:
```
Host - - [TimeStamp] "HTTP Request" Code ReplyBytes
```

### 1.2 Program Output
After processing the log file, the program should output the top 10 most visited web pages along with the total elapsed time. The output format is as follows:
```
Filename1 # of total visits
Filename2 # of total visits
...
Filename10 # of total visits
Total Elapsed Time: X seconds
```

### Usage
```
Compile the project using a C++ compiler.
Run the program with a server log file as input.
Review the output for the top 10 pages and performance metrics.
```

### Acknowledgments
```
Special thanks to OpenAI's GPT-4 and Bard for assistance in certain aspects of the project.
```
