# NYC Public School SAT Performance Analysis

## Description
This project analyzes SAT performance data from New York City public high schools to answer key questions that are critical for educational stakeholders, including policymakers, researchers, and parents. The analysis focuses on identifying top-performing schools in math, ranking schools by total SAT scores, and evaluating borough-level performance variability.

## Features
The analysis addresses three key questions:

- **Top Math Schools**: Which schools have average math scores above 80% of the maximum (640 points)?
- **Top 10 Schools by Total SAT**: Which schools have the highest combined SAT scores (math + reading + writing)?
- **Borough SAT Variability**: Which NYC borough exhibits the largest standard deviation in total SAT scores?

## Installation
Ensure Python 3.x and pandas are installed.

Install dependencies:

```bash
pip install pandas
```

## Usage
1. Place the dataset `schools.csv` in your working directory.
2. Run the provided Python script (Jupyter Notebook or similar environment):

```python
import pandas as pd
schools = pd.read_csv("schools.csv")
# ... [code as provided]
```

Results will be printed for each analysis.

## Data
The dataset `schools.csv` includes the following columns:

- **school_name**: Name of the school.
- **borough**: NYC borough (Manhattan, Brooklyn, etc.).
- **building_code**: Unique identifier for the school building.
- **average_math**: Average math SAT score.
- **average_reading**: Average reading SAT score.
- **average_writing**: Average writing SAT score.
- **percent_tested**: Percentage of students tested (may contain missing values).

## Results

### 1. Top Math Schools
Schools with average math scores exceeding 640/800:

| School Name                      | Average Math Score |
|----------------------------------|--------------------|
| Stuyvesant High School          | 754                |
| Bronx High School of Science    | 714                |
| Staten Island Technical High School | 711           |
| *(Full list: 10 schools)*       |                    |

### 2. Top 10 Schools by Total SAT
| School Name                      | Total SAT (Max 2400) |
|----------------------------------|----------------------|
| Stuyvesant High School          | 2144                 |
| Bronx High School of Science    | 2041                 |
| Staten Island Technical High School | 2041             |
| *(Full list: 10 schools)*       |                      |

### 3. Borough SAT Variability
Manhattan has the largest standard deviation in total SAT scores:

- **Number of Schools**: 89
- **Average SAT**: 1340.13
- **Standard Deviation**: 230.29

This indicates significant performance disparities among Manhattan schools compared to other boroughs.

## License
- **Dataset**: Publicly available (assumed for educational use).
- **Photo by Jannis Lucas on Unsplash** (Source).

*Note: This analysis helps identify excellence and inequities in NYC public school systems, offering actionable insights for improvement.*
