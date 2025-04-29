# Titanic Survival Prediction 🚢💔

![Titanic Survival Prediction](https://img.shields.io/badge/Download%20Releases-Click%20Here-brightgreen?style=for-the-badge&logo=github)

Welcome to the **Titanic Survival Prediction** repository! This project aims to predict passenger survival on the Titanic using a robust ensemble machine learning approach. By leveraging advanced techniques like stacking with Random Forest, Gradient Boosting, and Support Vector Machines (SVM), we achieved a Kaggle score of **0.77990**. This README will guide you through the project, its features, and how to get started.

## Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Project Overview

The Titanic disaster remains one of the most infamous maritime tragedies. In this project, we explore the factors that contributed to the survival of passengers. By analyzing historical data, we apply machine learning techniques to predict who survived and who did not. This project not only highlights the power of data science but also showcases the importance of feature engineering and model optimization.

## Key Features

- **Ensemble Learning**: Combines multiple models to improve prediction accuracy.
- **Feature Engineering**: Utilizes domain knowledge to create new features that enhance model performance.
- **Hyperparameter Tuning**: Optimizes model parameters for better results.
- **Visualization**: Uses Matplotlib to create informative plots that illustrate data insights.
- **Model Evaluation**: Employs precision and recall metrics to assess model performance.

## Technologies Used

This project incorporates a variety of tools and libraries, including:

- `GradientBoostingClassifier`
- `RandomForestClassifier`
- `SVC` (Support Vector Classifier)
- `LogisticRegression`
- `SimpleImputer`
- `StandardScaler`
- `OneHotEncoding`
- `Matplotlib`
- `Precision and Recall Metrics`

## Data

The dataset used in this project is derived from Kaggle. It includes various features such as:

- Passenger class
- Sex
- Age
- Siblings/Spouses aboard
- Parents/Children aboard
- Ticket fare
- Cabin number
- Embarked location

You can find the dataset in the [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data).

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/bayudwimulyadi/Titanic-Survival-Prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Titanic-Survival-Prediction
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

After installing the required packages, you can run the main script to train the model and make predictions.

1. Run the training script:
   ```bash
   python train.py
   ```

2. To make predictions on new data, use:
   ```bash
   python predict.py --input <your_input_file.csv>
   ```

3. For visualization, execute:
   ```bash
   python visualize.py
   ```

## Model Evaluation

To evaluate the model, we use precision and recall metrics. These metrics help us understand how well the model performs in identifying survivors. A confusion matrix is also generated to visualize the results.

You can find detailed evaluation results in the `evaluation` directory. This includes:

- Confusion Matrix
- Precision and Recall Scores
- ROC Curve

## Contributing

We welcome contributions to improve this project. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request.

Please ensure your code follows the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Links

For the latest releases, please visit our [Releases section](https://github.com/bayudwimulyadi/Titanic-Survival-Prediction/releases). Here, you can download the latest version of the project files.

![Titanic Survival Prediction](https://img.shields.io/badge/Download%20Releases-Click%20Here-brightgreen?style=for-the-badge&logo=github)

Feel free to explore the code, run the models, and contribute to the project. Together, we can uncover the stories behind the Titanic's passengers and enhance our understanding of survival prediction through data science.