# MLOps Assignment 2 — DistilBERT Goodreads Genre Classifier

Fine-tuning DistilBERT for multi-class book genre classification using the UCSD Goodreads dataset.
Trained on Kaggle GPU, tracked with Weights & Biases, and published to Hugging Face Hub.

## Setup Instructions

1. Clone this repo: `git clone https://github.com/Ashish-G25AIT2051/mlops-assignment2`
2. Install dependencies: `pip install -r requirements.txt`
3. Set environment variables:
   - `export WANDB_API_KEY=your_key`
   - `export HF_TOKEN=your_token`
4. Run the notebook on Kaggle (link below) with GPU T4 enabled

## Results

| Metric     | Score    |
|------------|----------|
| Accuracy   | 0.584375 |   ← fill from your eval output
| F1 Score   | 0.577125 |   ← fill from your eval output
| Eval Loss  | 2.334400 |   ← fill from your eval output

## Links
- GitHub: https://github.com/Ashish-g25ait2051/G25AIT2051_mlops-assignment2
- Kaggle Notebook: https://www.kaggle.com/code/ashishkg25ait2051/g25ait2051-assignment-2-final
- Hugging Face Model: https://huggingface.co/Ashish-G25AIT2051/distilbert-goodreads-genres
- W&B Dashboard: https://wandb.ai/g25ait2051-prom-iit-rajasthan/G25AIT2051_mlops-assignment2_Final/workspace?nw=nwuserg25ait2051