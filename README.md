# goalkeeper-position-recommender

## Table of Contents
- [Dependencies](#dependencies)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
  - [Running the Project](#running-the-project)
  - [Example Usage](#example-usage)

## Dependencies

The following Python libraries are required for the project:

- `h5py==2.10.0`
- `matplotlib==3.2.1`
- `numpy==1.18.4`
- `scikit-learn==0.22.2.post1`
- `scipy==1.4.1`

These dependencies are listed in the `requirements.txt` file. Ensure you have all these libraries installed before running the project.

## Installation Instructions

1. **Python Version**: Ensure you have Python 3.7.6 installed on your machine.
2. **Package Manager**: Install `pip`, the Python package installer.

## Usage

### Running the Project

This project is designed to be run within a Jupyter Notebook environment. The following steps will guide you through running the project:

1. **Start Jupyter Notebook**: Open the terminal, navigate to the project directory, and start the Jupyter Notebook server:
   ```bash
   jupyter notebook
   ```

2. **Open the Notebook**: In the Jupyter Notebook interface, open the notebook file corresponding to the project (e.g., `Regularization.ipynb`).

3. **Run the Cells**: Execute the cells in the notebook sequentially by selecting a cell and pressing `Shift + Enter`. This will run the code blocks and display the output inline.

### Example Usage

After setting up the environment and running the notebook, you can perform the following:

- **Loading the Dataset**: The project will load a dataset that is used to demonstrate various regularization techniques.

- **Non-Regularized Model**: You can train a model without any regularization and observe its performance.

- **L2 Regularization**: Implement L2 regularization to prevent overfitting and compare the performance with the non-regularized model.

- **Dropout**: Experiment with dropout regularization during forward and backward propagation and observe how it affects the model's learning process.

