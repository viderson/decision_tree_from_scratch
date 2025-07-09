# Decision Tree from Scratch 🌳🧠

This project presents a manual implementation of a **Decision Tree Classifier** using only base Python libraries like `NumPy` and `Pandas`. No external ML libraries (like `scikit-learn`) were used to build the model — everything is done from scratch for learning purposes.

## 📁 Project Structure

```
decision_tree_from_scratch/
├── data/
│   └── breast-cancer.csv           # Dataset for classification
├── notebook/
│   └── decision_tree.ipynb         # Full implementation in Jupyter Notebook
└── README.md
```

## 📊 Dataset

- **breast-cancer.csv**: Binary classification dataset
- Features: medical properties of cell samples
- Target: `0` for benign, `1` for malignant

## 🚀 Features

- Custom implementation of:
  - Decision tree construction using information gain (entropy)
  - Recursive tree building
  - Prediction based on traversing the tree
- Data preprocessing and splitting
- Accuracy evaluation on test data

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/decision_tree_from_scratch.git
   cd decision_tree_from_scratch
   ```

2. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook notebook/decision_tree.ipynb
   ```

3. Run each cell to:
   - Load and explore the dataset
   - Build and train the decision tree
   - Evaluate model performance

## 🛠 Tools Used

- Python 3.x
- NumPy
- Pandas
- Jupyter Notebook

## 🎯 Learning Goals

- Understand how decision trees work internally
- Build a classification model from scratch
- Apply entropy and information gain in real data
- Learn recursive algorithmic thinking

## 📌 Credits

- Dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- Author: Fw


