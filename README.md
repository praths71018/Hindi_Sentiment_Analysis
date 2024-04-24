# Introduction

This project uses different pre-trained models to predict the sentiments of people based on reviews in Hindi.

# Dataset Description

The dataset is a collection of Hindi reviews (2006 training examples) with 4 sentiments:

1. Happy
2. Sad
3. Angry
4. Neutral

# Models used

1. LSTM
2. BERT
3. mBERT
4. DistillBERT
5. IndicBERT

# Steps

## Transliterate

1. In the Transliterate Directory 1st git clone below repository:

```bash
   git clone https://github.com/yourusername/torch-transformer-hinglish2hindi-translator.git
   cd torch-transformer-hinglish2hindi-translator
```

(go to the repository to check how to use it)

2. Change the model_path in transliterate.ipynb to any of the models and run that file.

## Model building

1. Run Hindi_Sentiment_analysis.ipynb which uses IndicBert model.
