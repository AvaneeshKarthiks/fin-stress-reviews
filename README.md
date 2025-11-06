## Project Summary

This project uses financial sentiment models (**FinBERT**) and several app review datasets to measure sentiment and proxy for investor stress. The repository demonstrates how to load datasets from Hugging Face, run inference with a finetuned FinBERT model, and evaluate results.

---

## Datasets

### Primary datasets used or referenced in this project (Hugging Face / public links)

* **ProsusAI FinBERT (model):** [https://huggingface.co/ProsusAI/finbert](https://huggingface.co/ProsusAI/finbert)
* **FinRAD sample dataset:** [https://github.com/sohomghosh/FinRAD_Financial_Readability_Assessment_Dataset/blob/main/data_sample_1500.csv](https://github.com/sohomghosh/FinRAD_Financial_Readability_Assessment_Dataset/blob/main/data_sample_1500.csv)
* **Kaggle financial sentiment dataset:** [https://www.kaggle.com/datasets/sbhatti/financial-sentiment-analysis](https://www.kaggle.com/datasets/sbhatti/financial-sentiment-analysis)

### Datasets created/collected for this project (Hugging Face)

* **Zerodha app reviews:** [`Avaneeshkarthik/zerodha-app-reviews`](https://huggingface.co/datasets/Avaneeshkarthik/zerodha-app-reviews)
* **Coinbase app reviews:** [`Avaneeshkarthik/coinbase-app-reviews`](https://huggingface.co/datasets/Avaneeshkarthik/coinbase-app-reviews)
* **Binance app reviews:** [`Avaneeshkarthik/binance-app-reviews`](https://huggingface.co/datasets/Avaneeshkarthik/binance-app-reviews)
* **Groww app reviews:** [`Avaneeshkarthik/groww-app-reviews`](https://huggingface.co/datasets/Avaneeshkarthik/groww-app-reviews)

### FinBERT model used (finetuned)

* [`Avaneeshkarthik/finbert-finetuned`](https://huggingface.co/Avaneeshkarthik/finbert-finetuned)
