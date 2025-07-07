# Real-Time-Environmental-Sentiment-Classification-Using-Logistic-Regression-and-Emoji-Embeddings
This project performs data preprocessing and filtering of tweets related to environmental topics such as climate change, pollution, sustainability, etc.

Project Structure:
    Input File: File must contain minimum 2 columns named Tweet and Year
    Output File: File contains cleaned, environment-related tweets
    
Steps Involved:

    1. Data Collection
        Raw tweets are collected

    2. Preprocessing
        Cleaning: Removes URLs, mentions, hashtags, punctuation, HTML tags, etc.
        Normalization: Converts to lowercase, removes stopwords, and replaces slangs.
        Filtering: Keeps only tweets that mention environmental topics using a rich keyword list.

    3. Output
        Cleaned and filtered tweets are saved in a csv file

Key Features:

  Slang Dictionary: Translates informal Twitter language to formal equivalents.
  Environment Keyword Matching: Includes over 50+ environmental terms and hashtags.
