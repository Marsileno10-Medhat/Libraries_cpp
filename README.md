# C++ Utility Libraries

A collection of lightweight C++ header-only libraries providing utilities for date and period management, string manipulation, mathematical operations, and general-purpose functions. These classes are designed to be modular, easy to integrate, and follow OOP principles for robust code.

## Table of Contents
- [Overview](#overview)
- [Libraries](#libraries)
  - [clsDate](#clsdate)
  - [clsPeriod](#clsperiod)
  - [clsString](#clsstring)
  - [clsMath](#clsmath)
  - [clsUtil](#clsutil)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview
This repository contains a set of C++ utility classes implemented as header files, making them easy to include in any project. The libraries cover common tasks like date calculations, string processing, math checks, and utility functions for randomization and array handling. Built with encapsulation and modularity in mind, they support both static and instance-based methods for flexibility.

These libraries are ideal for applications requiring efficient data handling, such as scheduling tools, text processors, or simple games.

## Libraries

### clsDate
Handles date operations, including validation, calculations, and manipulations.

- **Key Features**:
  - Constructors for current date, specific dates, string parsing, or day-of-year.
  - Leap year checks, days/hours/minutes/seconds in year/month.
  - Date arithmetic: add/subtract days, weeks, months, years, etc.
  - Comparisons: before/after/equal, differences in days.
  - Validation: valid date/month/year/day.
  - Formatting: convert to string with custom separators.
  - Utilities: day of week, business/vacation days, end-of-period calculations.

### clsPeriod
Manages date periods (ranges), building on `clsDate`.

- **Key Features**:
  - Constructors for date objects or strings.
  - Overlap detection between periods.
  - Period length in days (include/exclude end date).
  - Check if a date is within a period.
  - Swap periods.
  - Calculate overlapping days between two periods.

### clsString
Provides advanced string manipulation utilities.

- **Key Features**:
  - Case conversions: upper/lower/invert for entire strings or first letters of words.
  - Counting: words, characters (vowels, capitals, smalls, punctuation, spaces).
  - Operations: trim (left/right/both), split into vectors, join vectors/arrays.
  - Reverse words, replace substrings (case-sensitive/insensitive).
  - Remove punctuation.
  - General replacement.

### clsMath
Offers mathematical utilities for numbers and arrays.

- **Key Features**:
  - Range validation, odd/even checks.
  - Reverse numbers, palindrome checks.
  - Array operations: sum, average, prime/non-prime checks and copying.
  - Count odd/even, positive/negative numbers in arrays.

### clsUtil
General-purpose utilities for various tasks.

- **Key Features**:
  - Print tabs, swap variables (int, double, string, char, dates).
  - Simple encryption/decryption (Caesar cipher).
  - Random generation: numbers, characters (small/capital/digit/special/mix), words, keys.
  - Array operations: print, fill with randoms, max/min, copy, shuffle, reverse, check existence, add elements.
  - Palindrome array checks.

## Installation
These are header-only libraries, so no compilation is required. Simply:
1. Clone the repository: `git clone https://github.com/yourusername/cpp-utility-libraries.git`
2. Include the desired header files in your C++ project (e.g., `#include "clsDate.h"`).

Ensure your compiler supports C++11 or later.