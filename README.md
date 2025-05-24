# Sentiment Analysis Visualization Tool

A comprehensive application analysis tool that generates visualizations of user review sentiments from app store data. This project helps quickly understand how users feel about different applications and identify trends in user feedback.

## Key Features

- **Data Filtering**: Automatically filters apps with sufficient review volume (over 1,000 reviews) for meaningful analysis
- **Sentiment Analysis**: Uses keyword matching to classify reviews as positive, neutral, or negative
- **Rating Grouping**: Organizes reviews into rating categories (1-2 stars, 3-4 stars, 4-5 stars)
- **Top Application Focus**: Highlights data from the top 5 most-reviewed applications
- **Interactive Visualization**: Generates detailed stacked bar charts showing sentiment distribution
- **User-Friendly Interface**: Includes a simple GUI for easy visualization generation

## How to Use

1. Prepare your dataset with columns: applicationName, review, and rating
2. Run the Python script to launch the GUI
3. Click "Generate Visualization" to create and display results in your browser

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- tkinter
- nltk

## Future Enhancements

- Integration with more advanced NLP libraries for improved sentiment analysis
- Additional visualization types and customization options
- Export functionality for generated reports

## Created by Kishan Chauhan

This tool provides valuable insights for app developers, product managers, and researchers analyzing user feedback patterns and application performance.
