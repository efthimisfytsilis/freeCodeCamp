# Machine Learning with Python

Welcome to my repository showcasing the projects I completed as part of the freeCodeCamp "Machine Learning with Python" course. These projects cover a range of machine learning concepts and applications. Feel free to explore each project's folder for more details.

## Projects

### I. [Rock, Paper, Scissors Challenge](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/rock-paper-scissors)
- **Description:** Introduction to _Reinforcement Learning_, by implementing the Q-Learning algorithm.

- **Files:**  
    - [`rps_game.py`](Rock_Paper_Scissors/rps_game.py): Provides boilerplate code containing four different opponent strategies to compete with our agent.  
    - [`rps_agent.py`](Rock_Paper_Scissors/rps_agent.py): Our agent implementation via a QLearning class.  
    - [`rps_agent_ens.py`](Rock_Paper_Scissors/rps_agent_ens.py): Modified agent to be used in an ensemble model.   
    - [`test_script.ipynb`](Rock_Paper_Scissors/test_script.ipynb): Simulating our bot competting against the others, displaying its win rate. Additionally, an alternative method that incorporates several instances of the agent (ensemble) is presented.

### II. [Cat and Dog Image Classifier](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/cat-and-dog-image-classifier)
- **Description:** Implementation of a CNN  that correctly classifies images of cats and dogs.

- **Files:**
    - [`cat_dog_classification.ipynb`](Cat_and_Dog_Image_Classifier/cat_dog_classification.ipynb): The training dataset undergoes augmentation through random transformations applied to the existing samples. A comparison is conducted between the deployed CNN and a pre-trained MobileNetV2 model to which a classifier layer is added to generate a _transfer learning_ model.

### III. [Book Recommendation Engine using KNN](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/book-recommendation-engine-using-knn)
- **Description:** Development of a model that suggests books similar to a given book using the Nearest Neighbors algorithm.

- **Files:**
    - [`book_recommendation_knn.ipynb`](Book_Recommendation_Engine/book_recommendation_knn.ipynb): Exploratory analysis of the book and rating dataframes is conducted. Model learns to identify books that are similar to each other based on the user ratings.

### IV. [Healthcare Cost Prediction using Regression](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/linear-regression-health-costs-calculator)
- **Description:** Predict healthcare costs of individuals using a regression algorithm.

- **Files:**
    - [`predict_health_costs_with_regression.ipynb`](Regression_Health_Costs_Calculator/predict_health_costs_with_regression.ipynb): Preprocessing involves the transformation of both numeric and categorical features. During the modeling stage, linear regression and gradient boosting models serve as a baseline and are compared to a dense NN,  employed with the premise to capture more complex relationships within the data.

### V. [SMS Spam Classification](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/neural-network-sms-text-classifier)
- **Description:** Introduction to _NLP_, by a machine learning model that predicts whether an SMS message is "ham" or "spam."

- **Files:**
    - [`sms_text_classification.ipynb`](SMS_Text_Classifier/sms_text_classification.ipynb): An imbalance in labels is idintified, resulting to thoughtful consideration to determine the appropriate course of action. The text messages undergo preprocessing, and a _bag-of-words_ model is constructed using linear regression as a baseline. Additionally, a dense neural network is implemented for comparative analysis, based on _word embeddings_.

## Setting Up
```
git clone https://github.com/efthimisfytsilis/freeCodeCamp.git
```
```
cd your-local-path/freeCodeCamp
```
- List of dependencies to run the projects: [`requirements.txt`](requirements.txt).

## Contributions and Feedback

This repository is open for contributions from anyone interested in improving the code or adding additional insights. Please feel free to open pull requests or leave comments on each project.

Special thanks to the author of this Reddit [post](https://www.reddit.com/r/learnprogramming/comments/115oopc/freecodecamps_machine_learning_certificate/) for offering valuable guidelines! As well as 

I hope this repository serves as a valuable resource for learning and exploring machine learning concepts in Python. Happy coding!





