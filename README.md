# Sentiment Analysis using DistilBERT and Twitter-RoBERTa

This project is my take on building a sentiment analysis system using deep learning. I fine-tuned a DistilBERT model on the twitter-financial-news-sentiment dataset to classify tweets into three categories: positive, neutral, or negative. After training, I achieved about 87.5% accuracy and a strong weighted F1 score — meaning the model isn't just guessing, it's actually understanding the vibe of financial tweets.
For inference (real-world predictions), I also built a lightweight custom sentiment pipeline using the CardiffNLP twitter-roberta-base-sentiment model. I added extra smart logic to handle tricky "neutral" cases better — because sometimes models like to exaggerate when the text is actually just "meh."

The project is built with:
- Hugging Face Transformers
- Datasets and Evaluation libraries
- PyTorch
- Scikit-learn for metrics
- Matplotlib & Seaborn for any visualizations
