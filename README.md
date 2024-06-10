# Sentiment Analysis Project

## Project Overview
This project performs sentiment analysis on tweets using the Sentiment140 dataset. The goal is to classify tweets as positive, negative, or neutral based on their content.

## Installation Instructions
To set up the project on your local machine, follow these steps:

1. **Clone the Repository:**
   Download the project files to your computer.
   ```bash
   git clone https://github.com/Bkandikonda95/SentimentAnalysisProject.git
2.Navigate to the Project Directory:
Move into the project folder.
cd SentimentAnalysisProject
3.Create a Virtual Environment (Optional but Recommended):
Set up a virtual environment to keep your project dependencies separate
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
4.Install the Required Dependencies:
pip install -r requirements.txt
Usage Instructions
To perform sentiment analysis on the dataset, follow these steps:

1.Run the Sentiment Analysis Script:
python sentiment_analysis.py
2.Jupyter Notebook:
If you prefer to explore the analysis interactively, you can use the provided Jupyter Notebook:
jupyter notebook SentimentAnalysis.ipynb
Project Structure
The repository contains the following files and directories:

sentiment_analysis.py: Script to perform sentiment analysis.
SentimentAnalysis.ipynb: Jupyter Notebook with detailed analysis and visualizations.
requirements.txt: List of dependencies required to run the project.
README.md: Project documentation.
data/: Directory containing the dataset.
Dataset
The project uses the Sentiment140 dataset, which is publicly available and contains 1,600,000 tweets classified as positive, negative, or neutral. The dataset is available here.

Sentiment Analysis Process
Data Loading:

Load the dataset from a CSV file.
Display the first few rows of the dataset.
Data Cleaning:

Remove special characters and convert text to lowercase.
Handle missing values.
Sentiment Classification:

Use the TextBlob library to classify tweets into positive, negative, or neutral sentiment.
Data Visualization:

Plot the distribution of sentiments using bar charts.
Results
The analysis reveals the distribution of sentiments in the dataset:

Positive tweets: 68,674 (48.12%)
Neutral tweets: 56,983 (40.00%)
Negative tweets: 34,493 (24.88%)

Model Performance
To evaluate the sentiment classification model, we split the dataset into training and testing sets. We used Logistic Regression for classification and achieved the following accuracy:

Model Accuracy: 96.57%
Contributions
Contributions are welcome! If you would like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
Acknowledgments
Special thanks to the creators of the Sentiment140 dataset and the open-source community for their valuable resources.
Contact
If you have any questions or suggestions, feel free to contact me: 

Name: [Bharath Kandikonda]
Email: [bkandikonda95@yahoo.com]
LinkedIn: [https://www.linkedin.com/in/bharath-kandikonda-63500387/]
