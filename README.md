# project1-NGS--sequence-analysis
Functions in this code can compare Next generation sequencing samples to a test reference. It can check for validity of samples, find mutations and analyse, summarise and compare results. 

This programme aims to analyse many short-read sequences attained through Next generation sequencing and compares them to a reference sequence to find mutations within and across samples and summarise data for further analysis.

To run, open notebook from GitHub Repository in Colab. First, libraries must be installed, own files must be uploaded or downloaded from a GitHub repository and loaded into Colab. Use own data as arguments in the designed functions. 

Parameters are given within functions, giving guidance as to what the function expects as well as type hints. Docstrings describe function and what to expect from them. Type hints are also given for outputs. Each function builds up on the next. To make use of this, assign the outputs a variable name and enter this as input into the next function.

As programming design patterns, accumulator patterns were chosen for updating accumulating values. Therefore, no manual addition had to occur, reducing coding load and reduction in calculation errors. Additions accumulate automatically, without the need of further adjustments. 
Defensive programming was another design pattern chosen. By checking data prior to using functions and ensuring invalid data is handled, the designed program will not crash and incorrect data outputs can be avoided. In this instance if conditionals were used. Other possible mechanisms to deal with invalid characters include raising errors and try and except. If conditionals were preferred over try/except as checks are easily performable and certain.

To test code, normal input was tested to ensure the program emitted the correct outputs. In addition, edge cases and invalid inputs were tested by passing valid yet unusual inputs such as empty strings through the program as well as reads of invalid lengths and reads with unsupported characters. 
