# Automated Personality Assessment from Text

## Overview
This project aims to predict Big Five personality traits from essays using machine learning techniques. The Big Five personality traits include Openness, Conscientiousness, Extraversion, Agreeableness, and Neuroticism (OCEAN). The project utilizes natural language processing (NLP) techniques to analyze text data and train machine learning models for personality trait prediction.

## Dataset
The dataset used in this project is sourced from Kaggle and consists of essays along with labels for each of the Big Five personality traits. Each essay is labeled according to whether the trait is present or not. The dataset is preprocessed to prepare it for training machine learning models.

## Tools and Libraries Used
- Python: Programming language used for development
- Pandas: Library for data manipulation and analysis
- Scikit-learn: Library for machine learning tasks such as data preprocessing, model training, and evaluation
- NLTK (Natural Language Toolkit): Library for NLP tasks such as tokenization, stemming, and lemmatization
- TfidfVectorizer: Feature extraction technique used to convert text data into numerical features
- Logistic Regression: Machine learning algorithm used for classification tasks
- GitHub: Version control system used for project collaboration and code management

## Project Structure
The project is structured as follows:
- `essays.csv`: CSV file containing the dataset of essays and personality trait labels
- `personality_prediction.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation
- `README.md`: Markdown file providing an overview of the project, dataset, tools, and libraries used
- `requirements.txt`: Text file listing the Python dependencies required to run the project

## Usage
To run the project, follow these steps:
1. Clone the repository: `git clone https://github.com/your_username/automated-personality-assessment.git`
2. Navigate to the project directory: `cd automated-personality-assessment`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Open and execute the `personality_prediction.ipynb` notebook using Jupyter or any compatible environment

## Results
The project achieves the following accuracies for predicting each Big Five personality trait:
- Extraversion (cEXT): 54.45%
- Neuroticism (cNEU): 59.92%
- Agreeableness (cAGR): 54.45%
- Conscientiousness (cCON): 55.47%
- Openness (cOPN): 59.92%

## Conclusion
Automated personality assessment from text shows promising results in predicting Big Five personality traits from essays. Further improvements can be made by experimenting with different machine learning algorithms, feature engineering techniques, and hyperparameter tuning.
