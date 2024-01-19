Absolutely! Below is a README template for your group project. You can modify it as needed to better fit the specifics of your project.

---

# CS 412 Course Projet - Prediction of student grades with ChatGPT Input

## Description

This project is a comprehensive data analysis and machine learning endeavor that involves parsing HTML data, feature engineering, prompt matching using NLP techniques, and building a predictive model using XGBoost. Our objective is to analyze conversations, likely from an interactive chatbot system ChatGPT, and predict numerical grades based on various features extracted from these interactions.

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
- `notebooks/`: Jupyter Notebooks with all the code and analysis.
- `src/`: Any additional source code or scripts used in the project.
- `README.md`: Documentation and guide for understanding and executing the project.

## Features

- **HTML Parsing**: Extracts data from HTML files, building useful mappings and data structures for analysis.
- **Feature Engineering**: Adds several features like sentiment analysis, word and character counts, readability scores, and keyword occurrences.
- **Prompt Matching**: Uses TF-IDF Vectorization and cosine similarity to match user prompts with predefined questions.
- **Model Building and Evaluation**: Utilizes XGBoost for predicting grades and evaluates the model's performance using metrics like MSE and R2 score.
- **Prediction Analysis**: Includes a detailed comparison of predicted grades versus actual grades.

## Authors

- Efe Cankaya
- Egemen Esen
