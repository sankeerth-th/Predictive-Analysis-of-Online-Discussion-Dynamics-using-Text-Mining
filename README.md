# Predictive-Analysis-of-Online-Discussion-Dynamics-using-Text-Mining
Data Mining - Fall Term 2023 - University of Memphis - Project Code Deliverables
# Sentiment Analysis on Reddit Comments Project

## Overview
This repository contains the code for a sentiment analysis project on Reddit comments, conducted by Sai Sankeerth Thallapally. The project aims to classify the sentiment of comments as either positive or negative using machine learning techniques. It includes three Python script files for different phases of the project and links to the required datasets.

## Files in the Repository

- `EXPERIMENT-1.ipynb`: Jupyter notebook for the first experiment.
- `EXPERIMENT-2.ipynb`: Jupyter notebook for the second experimental setup.
- `Final code.ipynb`: Jupyter notebook containing the final sentiment analysis model.

## Data Files

The large dataset and Word2Vec model files are not included in this repository, but can be downloaded from the following links:

- **Reddit Comments Dataset (May 2015)**:
  - Description: Contains Reddit comments from May 2015.
  - Size: Approximately 21 GB.
  - Download Link: [Reddit Comments May 2015 - Kaggle](https://www.kaggle.com/datasets/kaggle/reddit-comments-may-2015)

- **GoogleNews-vectors-negative300.bin**:
  - Description: Pre-trained Word2Vec model from Google News.
  - Size: About 3 GB.
  - Download Link: [GoogleNews Vectors Negative300 - Kaggle](https://www.kaggle.com/datasets/leadbest/googlenewsvectorsnegative300?rvi=1)

After downloading, place the `database.sqlite` (extracted from the Reddit Comments Dataset) and `GoogleNews-vectors-negative300.bin` files in the project directory alongside the Jupyter notebooks.

## How to Run the Code

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, nltk, textblob, gensim, keras, sklearn, imblearn, sqlite3

### Installation
1. Install Python: Download from [Python's official website](https://www.python.org/downloads/).

2. Install Jupyter Notebook:
```
   pip install notebook
``` 
3. Install Libraries:
```
pip install pandas nltk textblob gensim keras sklearn imblearn sqlite3
```

### Running the Notebooks
1. Open **Terminal (macOS/Linux)** or **PowerShell (Windows)**.
2. Navigate to the project directory with the `.ipynb` files.
3. Launch Jupyter Notebook:
```
jupyter notebook
```
4. Open the desired notebook from the Jupyter browser interface.
5. Run the notebook cells by pressing Shift + Enter, or use "Run All" in the toolbar.

## Troubleshooting
- Verify all libraries are installed.
- Restart the Jupyter notebook kernel if necessary.
- Check the file paths to `database.sqlite` and `GoogleNews-vectors-negative300.bin`.

## Contact
For any queries related to this project, please contact Sai Sankeerth Thallapally at sthllpll@memphis.edu.

    
