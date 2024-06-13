# Project : PersonalInterestMapper(Still under development)

# YouTubeInsights

---

YouTubeInsights is a tool that analyzes your YouTube search history to extract fields of knowledge and visualize your interests. This project leverages natural language processing (NLP) techniques to provide insights into the topics you are most interested in based on your search history.

## Features

- Load and preprocess YouTube search history data.
    - Go to https://takeout.google.com/settings/takeout?pli=1 and select deselect all and select Youtube and extract data
    - [Load]
- Extract and identify key topics from video titles.
- Visualize the distribution of topics using bar charts.
- Generate a word cloud for a visual representation of your interests.

## Requirements

- Python 3.6+
- Pandas
- Matplotlib
- WordCloud
- scikit-learn
- NLTK

## Road-Map

1. https://takeout.google.com/settings/takeout?pli=1 - Extracting Youtube data from google
2. Data is not organized so running program to convert into structured CSV file for data analysis
3. We have youtube link and video titles in string format so used NLP
    - **Tokenize the video titles**: Split the text into individual words or tokens.
    - **Remove stop words**: Remove common words that do not contribute much to the meaning, such as "the", "and", "is", etc.
    - **Stemming or Lemmatization**: Reduce words to their root form.
    - **Topic Extraction**: Use techniques like TF-IDF (Term Frequency-Inverse Document Frequency) or LDA (Latent Dirichlet Allocation) to extract topics.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](https://www.notion.so/LICENSE) file for details.

## Contact

For any questions or suggestions, please contact Abuthahir.dataset+PersonalInterestMapper@gmail.com
