## Problem statement: 
This project analyzes U.S. baby name data using a problem-driven approach inspired by a case study. The analysis goes beyond individual questions to explore long-term naming trends, gender ambiguity, and generational shifts.

## Dataset description

This project uses U.S. baby name data derived from Social Security records, covering births from 1910 onward. The dataset is organized into state-level text files, one for each of the 50 states and the District of Columbia, named using the state’s postal abbreviation (e.g., CA.txt, NY.txt).
Each record represents the number of babies given a specific first name in a particular state, year, and gender. The fields include:

- State code
- Gender (M or F)
- Year of birth
- First name
- Number of occurrences
  
Files are comma-separated and do not include headers. For privacy reasons, names with fewer than five occurrences in a given state and year are excluded from the dataset.

## Key Questions Explored:

- Please describe the format of the data files. Can you identify any limitations or distortions of the data?
- What is the most popular name of all time? (Of either gender.)
- What is the most gender ambiguous name in 2013? 1945?
- Of the names represented in the data, find the name that has had the largest percentage increase in popularity since 1980. Largest decrease?
- Can you identify names that may have had an even larger increase or decrease in popularity?

## Tools & Libraries used:

- Python
- Jupyter Notebook
- glob
- pandas
