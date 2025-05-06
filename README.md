# CITS4407 Assignment 2 – Board Games Analysis

This repository contains my submission for Assignment 2 of CITS4407.

## Structure

```
cits4407_assignment2/
├── data/                  # Contains raw and cleaned data files
├── empty_cells            # Script to count missing values per column
├── preprocess             # Script to clean and transform the dataset
├── analysis               # Script to analyze cleaned data and answer questions
├── .gitignore             # Prevents large data files from being tracked
├── README.md              # This file
```

## Instructions

Each script is executable. To run:

```bash
./empty_cells data/sample.txt ";"
./preprocess < data/sample.txt > data/sample_cleaned.tsv
./analysis data/sample_cleaned.tsv
```

Test files are stored in `data/` for reference only (not tracked in Git).
