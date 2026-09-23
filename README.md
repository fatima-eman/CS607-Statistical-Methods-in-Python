# CS-607 Statistical Methods in Python

This repository contains Python-based solutions for the statistical problem sets assigned in the CS-607 course. The aim of this project is to implement traditional statistical and mathematical methods using modern data science libraries, translating theoretical concepts into reproducible code.

## Project Overview
* **Subject:** Statistical & Mathematical Methods for Data Science (CS-607)
* **Program Context:** MSc Data Science
* **Reference Text:** Sheldon M. Ross, *Introduction to Probability and Statistics for Engineers and Scientists, 3rd Edition*

## Repository Structure
```text
CS607-Statistical-Methods-in-Python/
│
├── README.md                              
├── requirements.txt                       
│
├── data/                                  
│   └── (Raw CSV datasets extracted from assignment tables)
│
└── chapter_02/                            
    └── CH02_Descriptive_Statistics.ipynb

## Technologies & Libraries Used
* **Python 3.x**
* **Jupyter Notebook:** For interactive data analysis and documenting mathematical logic.
* **Pandas:** For data structures, frequency tables, and automated class interval grouping (e.g., using `value_counts(bins=k, normalize=True)`)[cite: 2].
* **Matplotlib & Seaborn:** For constructing visualizations such as relative frequency line graphs, pie charts, stem-and-leaf plots, and histograms.

## Setup & Execution

1. Clone this repository to your local machine:
   `git clone <your-repository-url>`

2. Navigate into the directory:
   `cd CS607-Statistical-Methods-in-Python`

3. Install the required dependencies:
   `pip install -r requirements.txt`

4. Launch the Jupyter environment to view the solutions:
   `jupyter notebook`