# CS 412 Course Project - Prediction of Student Grades with ChatGPT Histories

## Description

This project is a comprehensive data analysis and machine learning endeavor that involves parsing HTML data, feature engineering, prompt matching using NLP techniques, and building a predictive model using XGBoost. Our objective is to analyze conversations from ChatGPT that were used to solve a machine learning homework by students, and predict numerical grades based on various features extracted from these interactions.

## Results

MSE Train: 0.2268041237113402

MSE TEST: 38.88

R2 Train: 0.9986121426462421

R2 TEST: 0.653678419747456

## Getting Started

### Dependencies

- Python 3.6+
- Libraries: matplotlib, pandas, graphviz, bs4 (BeautifulSoup), scikit-learn, xgboost, textblob, textstat
- Jupyter Notebook

### Installing

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/efecankaya/cs412-course-project.git
   ```
2. Install the required Python packages:
   ```
   pip install matplotlib pandas graphviz bs4 scikit-learn xgboost textblob textstat
   ```

### Executing the Program

1. Open the Jupyter Notebook in your preferred environment (e.g., JupyterLab, VSCode, or classic Jupyter Notebook).
2. Run the cells in order to install libraries, import modules, process data, and build the model.

## Project Structure

- `data/`: Directory containing HTML files and other data used for analysis.
- `hw_score_predict.ipynb`: Jupyter Notebook with all the code and analysis.
- `Assingment.ipynb`: Jupyter Notebook of the machine learning homework that the students have solved with ChatGPT.
- `README.md`: Documentation and guide for understanding and executing the project.

## Features

- **HTML Parsing**: Extracts data from HTML files, building useful mappings and data structures for analysis.
- **Feature Engineering**: Adds several features like sentiment analysis, word and character counts, readability scores, and keyword occurrences.
- **Prompt Matching**: Uses TF-IDF Vectorization and cosine similarity to match user prompts with predefined questions.
- **Model Building and Evaluation**: Utilizes XGBoost for predicting grades and evaluates the model's performance using metrics like MSE and R2 score.
- **Prediction Analysis**: Includes a detailed comparison of predicted grades versus actual grades.

## Authors

- Efe Çankaya
- Egemen Esen
