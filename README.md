
# Predict Employee Attrition and Department Fit

Welcome to the **Employee Attrition and Department Prediction** project! This project uses a branched neural network to predict employee attrition and recommend the most suitable department for employees based on historical data. By leveraging deep learning, this project aims to assist HR teams in employee management and department allocation.

---

## Table of Contents
- [Introduction](#introduction)
- [How It Works](#how-it-works)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
Employee attrition is a critical challenge for HR teams, and identifying employees better suited for other departments can improve job satisfaction and performance. This project provides a neural network model to predict:
1. Whether an employee is likely to leave the company.
2. The department that best fits the employee.

---

## How It Works
1. **Data Collection and Preprocessing**  
   - Load the dataset (CSV format).  
   - Preprocess the data, including encoding categorical variables and scaling numerical features.  
   - Split the dataset into training and testing sets.  

2. **Neural Network Construction**  
   - Design a branched neural network with shared hidden layers and two output branches.  
   - Train the model to predict both attrition and department fit.  

3. **Prediction and Evaluation**  
   - Evaluate the model using accuracy and loss metrics for both outputs.  
   - Generate predictions for new employees.  

---

## Technologies Used
- **Python** – Programming language for model development and data processing.  
- **TensorFlow/Keras** – Deep learning framework used to build and train the neural network.  
- **Pandas** – Data manipulation and preprocessing.  
- **Scikit-Learn** – Tools for data splitting, scaling, and evaluation.  
- **Jupyter Notebook** – Interactive environment for developing and testing the model.  
- **Matplotlib** – Visualization of model accuracy and loss over training epochs.  

---

## Getting Started
Follow these steps to set up and run the project on your local machine.

### Prerequisites
Ensure you have the following installed:  
- **Python 3.10+**  
- **Anaconda (Optional for Virtual Environment Management)**  
- **Git**  

### Installation
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/YOUR_USERNAME/neural-network-challenge-2.git
   cd neural-network-challenge-2
   ```

2. **Create and Activate a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scripts\activate     # For Windows
   ```

3. **Install Dependencies**
   ```bash
   pip install tensorflow keras scikit-learn pandas matplotlib
   ```

---

## Usage

### Launch Jupyter Notebook
   ```bash
   jupyter notebook
   ```

### Run the Notebook
- Open `attrition.ipynb` and execute each cell step by step.
- The notebook covers data preprocessing, model training, and evaluation.
- After training, predictions are generated and displayed.

### Model Export
- The trained model is saved as `employee_attrition_department_model.h5`.
- You can reload the model later for predictions or further training.

---

## Project Structure
```bash
neural-network-challenge-2/
├── attrition.ipynb                         # Notebook with full implementation
├── employee_attrition_department_model.h5  # Trained neural network model
├── requirements.txt                        # (Optional) List of dependencies
└── README.md                               # Project documentation
```

---

## Contributing
Contributions are welcome!  
Follow these steps to contribute:

1. Fork the repository.  
2. Create a new branch:  
   ```bash
   git checkout -b feature-branch
   ```  
3. Commit your changes:  
   ```bash
   git commit -m "Add feature"
   ```  
4. Push the branch:  
   ```bash
   git push origin feature-branch
   ```  
5. Create a Pull Request.

---

## License
This project is licensed under the MIT License - see the LICENSE file for details.
