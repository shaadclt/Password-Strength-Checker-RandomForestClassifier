# Password Strength Checker using Random Forest Classifier

This project is a password strength checker that utilizes a Random Forest Classifier to determine the strength of a given password. The Random Forest Classifier is trained on a dataset of passwords labeled with their corresponding strength levels.

## Prerequisites

Before running the code, make sure you have the following dependencies installed:

- Python (3.x)
- Jupyter Notebook
- NumPy
- Pandas
- scikit-learn

## Getting Started

To get started, follow the steps below:

1. Clone the repository:

```bash
git clone https://github.com/shaadclt/Password-Strength-Checker-RandomForestClassifier.git
```

2. Change into the project directory:

```bash
cd Password-Strength-Checker-RandomForestClassifier
```

3. Install the required dependencies:

4. Run Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the `Password Strength Checker.ipynb` notebook in Jupyter.

6. Run the notebook cells to train the Random Forest Classifier and evaluate its performance.

## Dataset

The dataset used for training the classifier should be in CSV format with two columns: 'password' and 'strength'. The 'password' column contains the password strings, and the 'strength' column contains their corresponding strength levels (e.g., weak, medium, strong).

Ensure that your dataset is appropriately formatted and replace the `passwords.csv` file in the project directory with your own dataset.

## Model Training and Evaluation

The notebook guides you through the process of loading the dataset, preparing the data, training the Random Forest Classifier, and evaluating its performance. The classifier uses features such as password length, presence of digits, uppercase letters, and special characters to determine the password strength.

After running the notebook cells, you will see the accuracy of the classifier on the test set and a classification report that provides detailed performance metrics for each strength level.

## Customization

Feel free to modify the code to suit your specific requirements. You can experiment with different features, tweak the Random Forest Classifier parameters, or even try different machine learning algorithms for password strength classification.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Acknowledgments

- This project is inspired by the need to assess the strength of passwords in an automated and efficient manner.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


