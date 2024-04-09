# Multi-Label Text Translation and Preprocessing Project

This project expands upon the previous multi-label text classification project by incorporating text translation and preprocessing steps.

## Text Translation

The text translation part of the project aims to translate text from Spanish to English using machine translation models provided by the Hugging Face `transformers` library. The `MarianMTModel` and `MarianTokenizer` are utilized for translating Spanish text to English.

After translation, the translated text is saved to a CSV file and made available for download.

## Preprocessing

The preprocessing part of the project focuses on cleaning and preparing the text data for the classification task. Several preprocessing steps are applied to both the original and translated datasets, including:

- Removing URLs, mentions, hashtags, and HTML tags
- Demojizing emojis to text representations
- Removing punctuation and extra whitespace
- Converting text to lowercase
- Removing stopwords

The preprocessed datasets are then saved to CSV files for further analysis and model training.

## Conclusion

By incorporating text translation and preprocessing steps, this project aims to enhance the quality of the text data and improve the performance of multi-label text classification models. These preprocessing techniques help in reducing noise and irrelevant information from the text, leading to better model predictions and insights.

