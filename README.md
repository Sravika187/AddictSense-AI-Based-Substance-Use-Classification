# AddictSense-AI-Based-Substance-Use-Classification

AddictSense is a machine learning project that analyzes user-provided sentences and classifies them based on substance use. It identifies different substance-related categories and can also detect cases where no substance use is mentioned.

The project uses Natural Language Processing (NLP) and machine learning techniques to work with text data.

## Features

- Classifies user-provided text related to substance use
- Uses Natural Language Processing (NLP) for text processing
- Converts text into numerical features using TF-IDF
- Uses Logistic Regression for classification
- Uses Random Forest for classification
- Combines predictions from multiple models
- Detects text where no substance use is mentioned

## Technologies Used

- Python
- Natural Language Processing (NLP)
- Scikit-learn
- TF-IDF
- Logistic Regression
- Random Forest
- Jupyter Notebook

## How It Works

The project follows a simple machine learning workflow:

1. The user provides a sentence as input.
2. The text is processed for classification.
3. TF-IDF converts the text into numerical features.
4. The processed data is passed to the machine learning models.
5. Logistic Regression and Random Forest are used for classification.
6. The system returns the predicted category.

## Machine Learning Models

### Logistic Regression

Logistic Regression is used to classify the text into the categories learned from the training data.

### Random Forest

Random Forest is used as another classification model. It uses multiple decision trees to make the prediction.

### Ensemble Approach

The project uses both Logistic Regression and Random Forest to provide a combined classification approach instead of depending on only one model.

## Example

### Input
text
The person regularly consumes alcohol

#### OUTPUT
Predicted Category: Substance Use

### Project Workflow

User Input
    ↓
Text Processing
    ↓
TF-IDF Feature Extraction
    ↓
Logistic Regression
    +
Random Forest
    ↓
Classification Result

### Project Structure

AddictSense/
│
├── README.md
├── notebook.ipynb
└── other project files



### Installation
STEPS:
Clone the repository:
git clone https://github.com/Sravika187/AddictSense-AI-Based-Substance-Use-Classification.git

Go to the project folder:
cd AddictSense-AI-Based-Substance-Use-Classification

Install the required Python libraries:
pip install numpy pandas scikit-learn nltk matplotlib seaborn jupyter

Start Jupyter Notebook:
jupyter notebook

Open the project notebook and run the cells step by step.


### Applications
AddictSense can be used as a basic example of applying NLP and machine learning to text classification problems.
The project can also be extended with larger datasets and more advanced NLP techniques.

### Future Improvements
- Add a simple web interface
- Add more training data
- Try additional machine learning models
- Improve text preprocessing
- Add model accuracy and performance comparison
- Deploy the trained model as a web application
- Add an API for real-time predictions
  
### Disclaimer
This project is developed for educational and learning purposes. The results produced by the model should not be treated as a medical diagnosis or professional assessment.


### Author
Sravika Chowdavarapu


