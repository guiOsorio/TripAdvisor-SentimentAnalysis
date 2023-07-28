# TripAdvisor-SentimentAnalysis

This model uses a dataset found on Kaggle https://www.kaggle.com/datasets/arnabchaki/tripadvisor-reviews-2023?resource=download. This dataset contains reviews of guest stays in hotels from New Delhi.

This project consists of data exploration, preprocessing and building models for sentiment analysis. All models used are BERT-based.

Models:
- baseline model -> pre-trained Roberta model for sentiment analysis. More info here: https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment
- model #1 -> fine-tuned Roberta model for sentiment analysis. More info here: https://huggingface.co/gosorio/robertaSentimentFT_TripAdvisor 
- model #2 -> fine-tuned MiniLM model. More info here: https://huggingface.co/gosorio/minilmFT_TripAdvisor_Sentiment 
