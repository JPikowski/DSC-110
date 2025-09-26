# Introduction to R Programming

This lesson plan introduces the basics of R programming, including installing R and RStudio, working with data types and variables, using operators and control structures, defining functions, manipulating vectors and data frames, handling input/output, and exploring basic plotting. By the end, students will be able to write and run R scripts and perform basic data analysis.

## Lesson 1: Installing R and RStudio
Download and install R from CRAN
Install RStudio as the IDE for writing and running R code
Verify installation by launching RStudio and running version or R.version.string

## Lesson 2: Basic Data Types and Variables
Introduce core data types: numeric, integer, character, logical, factor
Assign variables using <- or =
Use print() and cat() to display output
Explore typeof() and class() functions

## Lesson 3: Operators and Expressions
* Arithmetic operators: +, -, *, /, ^, %%, %/%
* Comparison operators: ==, !=, <, >, <=, >=
* Logical operators: &, |, !
* Combine expressions and use ifelse() for inline logic

## Lesson 4: Control Flow
Conditional statements: if, else, else if
Loops: for, while, repeat
Use break and next to control loop behavior
Emphasize vectorized alternatives for efficiency

## Lesson 5: Functions
Define functions using function()
Use parameters and return values
Explore scope and default arguments
Example: mean_custom <- function(x) { return(mean(x)) }

## Lesson 6: Vectors, Lists, and Data Frames
Create and manipulate vectors with c(), indexing, and logical filtering
Work with lists and access elements using $ and [[ ]]
Create and modify data frames using data.frame(), subset(), and dplyr functions
Introduce tibbles from tidyverse

## Lesson 7: Input and Output
Read data with read.csv(), read.table(), and readr::read_csv()
Write data using write.csv() or write.table()
Use file.exists() and file.info() for file handling

## Lesson 8: Basic Plotting
Use plot(), hist(), boxplot() for quick visualizations
Introduce ggplot2 for layered, customizable plots
Discuss aesthetics, geoms, and themes

## Lesson 9: Project
Create a script or RMarkdown document that:
Loads and cleans a dataset
Performs basic analysis (summary stats, filtering)
Visualizes results
Outputs findings to a file or plot