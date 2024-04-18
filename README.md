# Student Loan Repayment Predictor

This repository contains a Jupyter Notebook which demonstrates the process of predicting student loan repayment success using a neural network model built with TensorFlow/Keras. The project covers data preparation, model building, training, evaluation, and prediction stages, using a dataset of student loans.

## Project Structure

The notebook is organized into several main sections:

1. **Data Preparation**: Loading and preprocessing data to prepare it for use with a neural network model.
2. **Model Building**: Constructing a deep learning model to predict loan repayment.
3. **Model Training and Evaluation**: Compiling, training, and evaluating the neural network.
4. **Prediction**: Making predictions on new data and evaluating those predictions.
5. **Discussion**: Discussing the creation of a recommendation system for student loans.

### Files

- **student-loans.csv**: The dataset used for training and evaluating the neural network model.
- **student_loans.keras**: The saved trained model ready for making predictions.
- **Student Loan Risk with Deep Learning.ipynb**: The Jupyter Notebook containing the project workflow.

## Installation and Usage

To run this project, you need to have Python installed along with Jupyter Notebook or JupyterLab. Follow the steps below to set up and run the notebook:

### Prerequisites

- Python 3.8 or later
- pip
- Jupyter Notebook or JupyterLab

### Libraries

Install the required Python libraries using pip:

```bash
pip install pandas tensorflow scikit-learn matplotlib
```

### Running the Notebook

1. Clone this repository to your local machine.
2. Navigate to the repository directory in your terminal.
3. Start Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
# or
jupyter lab
```

4. Open the `Student Loan Risk with Deep Learning.ipynb` notebook and run the cells sequentially.

## Notebook Sections

- **Data Preparation**:
  - Loading data
  - Preprocessing data (feature scaling)
  - Splitting data into training and testing sets
- **Model Building**:
  - Designing a sequential model with multiple layers
- **Model Training and Evaluation**:
  - Compiling the model with appropriate metrics
  - Training the model and plotting training history
  - Evaluating the model on test data
- **Prediction**:
  - Making and saving predictions
- **Discussion**:
  - Answering questions related to building a recommendation system

## Contributing

Contributions to this project are welcome. Please ensure to update tests as appropriate and adhere to the existing coding style.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

- **Your Name** - [Your Email](mailto:kenstager@hotmail.com)
