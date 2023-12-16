![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Python](https://img.shields.io/badge/python-v3.11-blue)
![Streamlit](https://img.shields.io/badge/streamlit-v1.28.0-orange)
![Plotly](https://img.shields.io/badge/plotly-v5.18.0-lightgrey)
![NLTK](https://img.shields.io/badge/NLTK-v3.8.1-green)


# Diary Tone Analysis

This project features a Python application utilizing Streamlit and Plotly for visualizing the sentiment analysis of diary entries over time. It employs NLTK's SentimentIntensityAnalyzer to assess the positivity and negativity in the diary texts.

## Overview

The application reads diary entries stored as `.txt` files in a specified directory (`diary/`), analyzes their sentiment, and displays the results in an interactive web dashboard. The sentiment analysis focuses on two aspects: positivity and negativity, tracked over the dates of the diary entries.

## Features

- **Sentiment Analysis**: Leverages NLTK's SentimentIntensityAnalyzer to evaluate the emotional tone of the diary texts.
- **Data Visualization**: Uses Plotly to create line charts representing the positivity and negativity trends over time.
- **Streamlit Dashboard**: Provides an interactive web interface to display the analysis results.

## Installation

Before running the application, ensure you have the following dependencies installed:

1. **Python**: The application is written in Python. Make sure Python is installed on your system.
2. **Streamlit**: This can be installed via pip:
   ```bash
   pip install streamlit
   ```
3. **Plotly**: For generating the visualizations.
   ```bash
   pip install plotly
   ```
4. **NLTK**: Natural Language Toolkit, used for sentiment analysis.
   ```bash
   pip install nltk
   ```

## Usage

1. Place your diary entries as `.txt` files in the `diary/` folder. Each file should be named in a way that the date can be extracted from the filename.
2. Run the Streamlit application:
   ```bash
   streamlit run main.py
   ```
3. The web interface will open in your default browser, where you can view the sentiment analysis results.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Screenshot of the App


![Screenshot 2023-12-16 at 4.19.26 AM.png](..%2F..%2F..%2F..%2F..%2FDesktop%2FScreenshot%202023-12-16%20at%204.19.26%E2%80%AFAM.png)