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

### 1.3 Tasks
#### Task 1: Implement a Custom Hash Table
- Implement a custom hash table as a C++ class.
- Store filenames and the corresponding number of visits in the hash table.
- No restrictions on the choice of the hash function and collision resolution method.

#### Task 2: Use `std::unordered_map`
- Utilize the `std::unordered_map` data structure to store filenames and their visit counts.

#### Task 3: Efficiency Comparison
- Implement a program to measure the total time from reading the log file to printing the top 10 most visited pages.
- Compare the time efficiency between the custom hash table and `std::unordered_map`.

### 1.4 Notes
- Efficiently find the top 10 most visited pages using heap data structures.
- Utilize the C++ standard library for needs other than the hash table implementation.

## 2. Submission

### 2.1 Files to Submit
1. Source code in a zip file.
2. Report (PDF) containing:
   a. Program output with total elapsed time screenshots (one for custom hash table, one for `std::unordered_map`).
   b. Detailed explanation of:
      - Hash table implementation (data structures, collision resolution method, and hash function).
      - Top 10 method (data structures and algorithms used).

## 3. Bonuses

Bonus points are awarded for:
- Good coding styles and object-oriented programming skills.
- Different collision resolution methods and their comparison.
- Innovative data structures and algorithms for faster execution.
- Any other notable features, thoroughly explained.

Clearly document and explain any extra efforts made.
