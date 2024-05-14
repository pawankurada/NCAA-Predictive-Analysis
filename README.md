# NCAA Women's Basketball Consumer Activity Prediction

This project utilizes an XGBoost model to predict consumer activity types (e.g., Primary purchase, Multiple purchase) based on NCAA Women's Basketball data. The notebook includes data preprocessing, model training, and evaluation steps.

## Table of Contents

- [Project Overview](#project-overview)
- [Data](#data)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project aims to predict consumer activity types using historical NCAA Women's Basketball data. The main steps include data cleaning, encoding categorical variables, training an XGBoost classifier, and evaluating the model's performance.

## Data

The dataset used in this project includes training and test sets:
- `DIWBB_Training.csv`
- `DIWBB_Test.csv`

The data files should be placed in a `data` directory within the project folder.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- XGBoost

You can install the required packages using the following command:

```bash
pip install pandas numpy scikit-learn xgboost
```
## Installation

Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/yourusername/NCAA-WBB-Consumer-Activity-Prediction.git
cd NCAA-WBB-Consumer-Activity-Prediction
```
Ensure that the data files are in the `data` directory.

## Usage

Run the Jupyter Notebook to execute the project steps. The notebook includes detailed comments and explanations for each step.
```bash
jupyter notebook xgboost-model.ipynb
```
## Model

The project uses an XGBoost classifier to predict consumer activity types. The workflow includes:
1. Loading the data
2. Handling missing values
3. Encoding categorical variables
4. Splitting the data into training and test sets
5. Training the XGBoost model
6. Evaluating the model's performance

## Evaluation

Model performance is evaluated using accuracy metrics. The notebook provides a detailed evaluation section that compares the predicted and actual consumer activity types.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
