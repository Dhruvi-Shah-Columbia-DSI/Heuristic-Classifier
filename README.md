# Hot Water Flow Detection Project

## Overview
This project implements a methodology to detect hot water flow using temperature data. A machine learning model analyzes temperature differentials to categorize the flow conditions effectively.

## Technical Description
The model utilizes temperature readings—outlet, ambient, and inlet—to compute a score based on pre-determined thresholds. These thresholds are optimized using a brute-force approach to maximize the F1 score, which balances precision and recall for our imbalanced dataset.

## Repository Structure
- Contains the Jupyter notebook `Plentify_WorkProduct_Final_Dhruvi_Shah.ipynb` which includes all exploratory data analysis, model development, and evaluations.

## Setup and Execution
```bash
# Clone the repository
git clone https://github.com/Dhruvi-Shah-Columbia-DSI/Heuristic-Classifier.git
cd Heuristic-Classifier/

# Run the notebook
jupyter notebook Plentify_WorkProduct_Final_Dhruvi_Shah.ipynb
```

## Contributing
Contributions to enhance the methodology or model are welcome. Please ensure to follow best practices for code quality and documentation.

---

This version emphasizes the project's technical components and streamlined repository structure for GitHub users interested in the analytical and development aspects.
