# Email Spam Detection Using Machine Learning (NLP)

<!-- PROJECT DESCRIPTION -->

## Project description

Email spam detection system is used to detect email spam using Machine Learning technique called Natural Language Processing and Python, where we have a dataset contain a lot of emails by extract important words and then use naive classifier we can detect if this email is spam or not.

<!-- PREREQUISTIES -->

## Prerequisites

This is list of required packages and modules for the project to be installed :

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- NLTK
- seaborn
- Matplotlib

Install all required packages :

```sh
 pip install -r requirements.txt
```

<!-- THE DATASET -->

## The Dataset

Human activites dataset contain about 5728 record which is a sample of an email
and a target column "spam" which describe the state of an email spam or not.

<!-- CODING SECTIONS -->

## Coding Sections

In this part we will see the project code divided to sections as follows:
<br>

- Section 1 | The Data :<br>
  In this section we aim to do some operations on the dataset before training the model on it,
  processes like :

  1. Data Loading : Load the dataset
  2. Data Visualization : Visualize dataset features
  3. Data Cleaning : Remove stopwords and duplicates values
  4. Data Splitting : Split the dataset into training and testing sets<br><br>

- Section 2 | The Model :<br>
  The dataset is ready for training, so we create a naive classifier using scikit-learn and thin fit it to the data, and finally we evaluate the model by getting accuracy, classification report and confusion matrix<br>

<!-- INSTALLATION -->

## Installation

1. Clone the repo
   ```sh
   git clone https://github.com/virajbhartiya/Spam-Email-Detection-NLP.git
   ```
2. Open 'main.ipynb' in Google Colab or VScode or Jupyter Notebook
3. Run the code
