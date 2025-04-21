<a name="readme-top"></a>

<!--
!!! IMPORTANT !!!
This README is an example of how you could professionally present your codebase. 
Writing documentation is a crucial part of your work as a professional software developer and cannot be ignored. 

You should modify this file to match your project and remove sections that don't apply.

REQUIRED SECTIONS:
- Table of Contents
- About the Project
  - Built With
  - Live Demo
- Getting Started
- Authors
- Future Features
- Contributing
- Show your support
- Acknowledgements
- License

OPTIONAL SECTIONS:
- FAQ

After you're finished please remove all the comments and instructions!

For more information on the importance of a professional README for your repositories: https://github.com/microverseinc/curriculum-transversal-skills/blob/main/documentation/articles/readme_best_practices.md
-->

<div align="center">

</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 Machine Learning Insights into Titanic Survival](#about-project)
- This project explores survival patterns in the Titanic dataset, revealing key insights:

          - Gender Disparity: Women had a 74.20% survival rate, compared to 18.89% for men, reflecting the "women and children first" protocol.
          - Age Impact: Children (under 13) survived at 57.97%, while teenagers had a 41.05% rate.
          - Model Performance: The ensemble model achieved a validation accuracy of 84.17% and a training accuracy of 90.35%, with a Kaggle score of 0.77990.


- [🛠 PYTHON](#built-with)
    - Python: Core programming language.
    - Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn.
    - Jupyter Notebook: Analysis in TitanicSurvivalPrediction.ipynb
- [Key Features](#key-features)
     - The stacking ensemble will use the RandomForestClassifier, GradientBoostingClassifier, and SVC, using LogisticRegression as the meta-classifier.
     - Feature engineering: Added FamilySize, IsAlone, Title, and binned Age and Fare.
     - Hyperparameter tuning with RandomizedSearchCV and StratifiedKFold cross-validation.
- [💻 Getting Started](#getting-started)
    - To get a local copy up and running, follow these steps.
  - [Prerequisites](#prerequisites)
    - Python 3.x
    - Jupyter Notebook
    - Git
  - [Setup](#setup)
     - Clone this repository: `git clone https://github.com/Marlyn-Mayienga/TitanicSurvivalPrediction.git`
  - [Install](#install)
     - Install dependencies: `pip install numpy pandas matplotlib seaborn scikit-learn`
  - [Usage](#usage)
     - Ensure `train.csv` and `test.csv` from the Kaggle Titanic competition are in the project directory.
     - Open `TitanicSurvivalPrediction.ipynb` in Jupyter Notebook.
     - Run all cells to reproduce the analysis, train the model, and generate submission predictions.
- [👥 Authors](#authors)
   - 👤 **Marlyn Mayienga**

- GitHub: [@Marlyn_Mayienga](https://github.com/Marlyn_Mayienga)
- Twitter: [@Merl_Mayienga](https://twitter.com/M_ayienga)
- LinkedIn: [Marlyn_Mayienga](https://linkedin.com/in/Marlyn_Mayienga)
- [🔭 Future Features](#future-features)
    - Incorporate additional ensemble techniques (e.g., XGBoost).
    - Explore advanced feature interactions for improved accuracy.
    - Add visualizations of survival patterns by class and embarkation port.

  Contributions, issues, and feature requests are welcome!

- [🤝 Contributing](#contributing)
   - Feel free to fork the repository, submit pull requests, or open issues for bugs and feature suggestions. Check the issues page for ongoing tasks
- [⭐️ Show your support](#support)
   - Give a ⭐️ if you like this project! Your support motivates further development.
- [🙏 Acknowledgements](#acknowledgements)
  - Kaggle: For providing the Titanic dataset and competition platform.
  - Scikit-learn Team: For robust machine learning tools.
  - References:
      - Zhou, Zhi-Hua. Ensemble Methods: Foundations and Algorithms.
      - Elinder, M., & Erixson, O. (2012). Gender, social norms, and survival in maritime disasters. PNAS.
- [❓ FAQ (OPTIONAL)](#faq)
- [📝 License](#license)
   - This project is [MIT](./LICENSE) licensed.

_NOTE: we recommend using the [MIT license](https://choosealicense.com/licenses/mit/) - you can set it up quickly by [using templates available on GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository). You can also use [any other license](https://choosealicense.com/licenses/) if you wish._

<p align="right">(<a href="#readme-top">back to top</a>)</p>
