# Emoji Usage and Tone Analysis in Reddit Discussions

## Overview

This project analyzes how emojis such as the crying emoji and skull emoji are used across Reddit communities. Using Python and pandas, the study examines emoji intensification and differences between informal and serious communication styles.

## Key Features

* Emoji detection (crying and skull emoji)
* Emoji intensity analysis
* Tone classification (serious vs informal)
* Subreddit category comparison (memes, gaming, sports, news, politics)
* Interactive dashboard using ipywidgets

## Dataset

This project uses the "1 Million Reddit Comments from 40 Subreddits" dataset from Kaggle:

https://www.kaggle.com/datasets/smagnan/1-million-reddit-comments-from-40-subreddits

### How to get the data:
1. Go to the link above
2. Click "Download"
3. Extract the ZIP file
4. Locate the file: `kaggle_RC_2019-05.csv`

### How to use it:
- When running the notebook in Google Colab:
  - Upload `kaggle_RC_2019-05.csv` when prompted

## Methods

The dataset was processed using Python in Google Colab. Pandas was used for data cleaning and grouping, while regular expressions were used to detect emoji patterns. Additional features such as emoji type, emoji intensity, and tone classification were engineered to support analysis.

## Results

The analysis shows that emojis are primarily used in informal contexts to intensify tone and create humor, while serious discussions (such as politics and news) contain minimal emoji usage.

## Tech Stack

* Python
* pandas
* regex
* ipywidgets
* Google Colab

## How to Run

1. Clone the repository
2. Install dependencies
3. Run the notebook

## Author

Ragavardhini Pattangi
