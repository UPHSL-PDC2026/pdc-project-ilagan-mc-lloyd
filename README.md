# Parallel Data Processing – Midterm Iteration 1

## Project Overview
This project performs analytics on a banking dataset (FraudShield_Banking_Data.csv) using sequential and parallel (multiprocessing) implementations. Three data operations are implemented:
- Filtering transactions above 5000
- Sum aggregation by category
- Average aggregation by category

Performance is measured and compared.

## Tools & Technologies
- Python 3.8+
- Jupyter Notebook / Google Colab
- pandas, numpy, multiprocessing, time

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open `performance_analysis.ipynb` in Jupyter Notebook or Colab.
4. Run all cells. Make sure the dataset is in the same directory (or update the file path).

## Team Members & Roles
- Ilagan, Mc Lloyd S – Developer & Analyst


## Results Summary
Version              Time (seconds) 
--------------------------------------------------
Sequential           0.2057         
Parallel             0.8132         
Speedup              0.25           x
Efficiency           12.65%         
