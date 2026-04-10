# Numpy-Data-Analysis
A Python-based  project work demonstrating efficient data analysis using NumPy, including sorting techniques, large-scale data simulation, and intelligent data filtering with vectorized operations.
 Features
Manual vs NumPy-based sorting comparison
Large dataset generation and statistical analysis
Boolean indexing for intelligent data filtering
Efficient computations using NumPy (no loops where possible)
 Tasks Implemented
 Task 1: Sorting Analysis
Implement sorting using a while loop (manual approach)
Sort 150 elements using NumPy’s built-in sort
Compare performance and efficiency
 Key Insight

NumPy sorting is significantly faster and more optimized than manual sorting due to internal vectorized operations and efficient algorithms.

 Task 2: Scalable Data Simulation
Generate a 1000 × 4 matrix of random floating-point values
Each row represents a sample (e.g., flower dataset simulation)
Compute:
Mean of each column
Standard deviation of each column
Use NumPy’s axis parameter (no loops)
 Example
import numpy as np

data = np.random.rand(1000, 4)

mean = np.mean(data, axis=0)
std_dev = np.std(data, axis=0)

print("Mean:", mean)
print("Standard Deviation:", std_dev)
 Task 3: Intelligent Data Filtering
Work with dataset (e.g., Iris dataset format)
Apply Boolean Indexing
Filter rows where Petal Length > 3
 Example
filtered_data = data[data[:, 2] > 3]
 Technologies Used
Python 
NumPy 
(Optional) Matplotlib 📈
📂 Project Structure
numpy-data-analysis-lab/
│
├── task1_sorting.py
├── task2_simulation.py
├── task3_filtering.py
├── README.md
⚙️ How to Run
1️.Clone the repository
git clone https://github.com/Aaditya69Kumar/Numpy-Data-Analysis.git
2️. Navigate to project folder
cd numpy-data-analysis-lab
3️. Run the scripts
python task1_sorting.py
python task2_simulation.py
python task3_filtering.py

Add performance benchmarking (time analysis)
Use real-world datasets (Iris, CSV files)
👨‍💻 Author

Aaditya Kumar
