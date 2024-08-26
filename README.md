# Sentiment Analysis of Etsy Reviews

This project was developed during an internship at Forsk Coding and focuses on performing sentiment analysis on reviews from Etsy's jewelry section using machine learning techniques. The goal is to classify customer feedback into positive or negative sentiments.

## Project Structure

- **etsy_scrapper.py**: Scrapes reviews from Etsy.
- **Creating_model_and_pickel_file.py**: Trains the sentiment analysis model.
- **Data_spilting.py**: Splits the dataset for training and testing.
- **Creating_pie_chart.py**: Generates a pie chart of sentiment distribution.
- **Word_Cloud_generator.py**: Creates a word cloud of frequent words.
- **UI_of_model.py**: Provides a local UI for model interaction.

## Features

- **Sentiment Classification**: Categorizes reviews into positive or negative.
- **Visualization**: Includes pie charts and word clouds.
- **Interactive UI**: Allows manual sentiment checking.
- **Model Persistence**: Saves the trained model for future use.

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/Pranava-Kailash/Sentimental-Analysis-of-Etsay-Reviews.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the UI:
    ```bash
    python UI_of_model.py
    ```

## Data Source

The reviews are scraped from [Etsy](https://www.etsy.com/) using the **etsy_scrapper.py** script.

## Results

- Sentiment distribution visualized with pie charts.
- Word cloud showcasing frequent words.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was completed during an internship with Forsk Coding.
