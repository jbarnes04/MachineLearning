# Perceptron and Adaline Implementations  

This repository contains custom implementations of **Perceptron** and **Adaline** algorithms, along with preprocessing steps and comparisons to **scikit-learn** implementations.  

The project uses the **Adult dataset** (`project_adult.csv` and `project_validation_inputs.csv`) to perform binary classification on income levels (`<=50K` or `>50K`).  

---

## Features  
- Custom **Perceptron** implementation  
- Custom **Adaline** implementation (gradient descent)  
- Preprocessing pipeline:  
  - Handling missing values  
  - One-hot encoding categorical variables  
  - Standardizing numerical features  
- Integration with **scikit-learn** classifiers for comparison  
- Accuracy evaluation and visualization of learning performance  

---

## Project Structure  
```
.
├── Group_26_Project1_Code.ipynb   # Jupyter notebook with full code
├── project_adult.csv              # Training dataset (not included here)
├── project_validation_inputs.csv  # Validation dataset (not included here)
└── README.md                      # Project documentation
```

---

## Installation  

Clone the repository:  
```bash
git clone https://github.com/jbarnes/MachineLearning.git
cd your-repo-name
```

Install dependencies:  
```bash
pip install -r requirements.txt
```

**Requirements:**  
- Python 3.8+  
- NumPy  
- Pandas  
- Matplotlib  
- scikit-learn  

---

## Usage  

1. Open the Jupyter notebook:  
   ```bash
   jupyter notebook Group_26_Project1_Code.ipynb
   ```

2. Run all cells to:  
   - Preprocess the dataset  
   - Train and evaluate the custom Perceptron and Adaline models  
   - Compare results with scikit-learn implementations  

---

## Results  
- Custom implementations achieve comparable performance to scikit-learn models on the Adult dataset.  
- Preprocessing (encoding + scaling) significantly improves accuracy.  
- Visualizations show error convergence and decision boundaries.  

---

## Authors  
Group 26 – Jodi Barnes & Lauren Moffett  
