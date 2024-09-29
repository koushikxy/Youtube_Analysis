# Youtube Data Analysis

This repository contains a comprehensive Python script for analyzing YouTube comments. The script performs several key tasks including reading and processing comments, sentiment analysis, word cloud generation, emoji frequency analysis, and data aggregation from multiple sources. It also includes capabilities for exporting data to CSV and SQLite database formats.

## Features
- Reading and Cleaning Data:

    - Imports comments data from a CSV file.
    - Handles missing values by dropping rows with empty comment_text.
- Sentiment Analysis:

    - Uses TextBlob to calculate sentiment polarity for each comment.
    - Segregates comments into positive and negative categories based on sentiment  scores.
- Word Cloud Generation:

    - Creates word clouds for positive and negative comments to visualize common words and phrases.
- Emoji Analysis:

    - Analyzes and identifies the most frequently used emojis in the comments.
    - Provides a list of the top 10 most common emojis.
- Data Aggregation:

    - Aggregates data from multiple CSV files into a single DataFrame.
    - Removes duplicate entries to ensure clean data.
- Exporting Data:

    - Exports a sample of the aggregated data to a CSV file.
    - Inserts data into an SQLite database for further analysis.
- Visualization:

    - Utilizes Plotly to create interactive bar charts for emoji frequency.

      Dataset Zip File Link : https://drive.google.com/file/d/1-26ljtH9IhEFK3cRozxughBg-XnprqWA/view?usp=sharing
## Dependencies

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `textblob`
- `wordcloud`
- `emoji`
- `sqlalchemy`
- `plotly`

## Conclusion

This YouTube data analysis script is a powerful tool for understanding user sentiments and trends in YouTube comments. By leveraging various Python libraries, it provides a comprehensive analysis and visualization workflow, making it easier to derive meaningful insights from large datasets.
