# Visibility Bias and Engagement Inequality in 2024 U.S. Election Discourse on X


## Requirements

* Python 3.10+

Install dependencies:

```bash
pip install pandas numpy matplotlib scipy scikit-learn statsmodels tqdm seaborn
```

## Running the Project

1. Open `CS260_FinalProject.ipynb`.
2. Run all cells from top to bottom.
3. Optionally modify `MAX_FILES` to control how much data is processed.

The notebook will automatically:

* Load and preprocess the dataset
* Generate visualizations
* Perform statistical analysis
* Run clustering and machine learning experiments

## Dataset

Dataset source:

https://github.com/sinking8/x-24-us-election

For computational feasibility, we used a sampled subset of the dataset spanning multiple months.

Files used:

* may_july_chunk_10.csv.gz
* may_july_chunk_207.csv.gz
* may_july_chunk_247.csv.gz
* may_july_chunk_289.csv.gz
* may_july_chunk_422.csv.gz
* aug_chunk_23.csv.gz
* aug_chunk_52.csv.gz
* aug_chunk_68.csv.gz
* september_chunk_62.csv.gz
* september_chunk_124.csv.gz
* september_chunk_138.csv.gz
* octobergap_chunk_11.csv.gz
* octobergap_chunk_46.csv.gz
* november_chunk_64.csv.gz

## Project Workflow

### Data Collection

* Downloaded election discussion data from the public repository.
* Loaded selected files into a Pandas DataFrame.

### Data Cleaning

* Parsed timestamps and dates.
* Cleaned engagement metrics.
* Handled missing values.
* Standardized text fields.
* Created derived engagement features.

### Exploratory Data Analysis

* Dataset summary statistics.
* Tweet volume trends.
* Candidate mention frequencies.
* Engagement and visibility distributions.

### Statistical Analysis

* Examined relationships between engagement and visibility.
* Compared engagement patterns across political discussions.

### Machine Learning Analysis

* Applied clustering methods to identify groups of tweets with similar engagement and visibility characteristics.

