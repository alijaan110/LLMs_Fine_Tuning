# Sentiment Analysis on IMDB Movie Dataset

This project involves performing **Sentiment Analysis** on the IMDB Movie Dataset using the **Llama3.2-1B LLM model**. The goal was to classify movie reviews as positive or negative and enhance the model's performance through fine-tuning. The project demonstrated a significant accuracy improvement from **69.3%** (pre-trained) to **95.7%** (fine-tuned).

## Dataset Overview

- **Dataset**: IMDB Movie Reviews  
- **Total Samples**: 3,000  
  - **Positive Reviews**: 1,500  
  - **Negative Reviews**: 1,500  

## Model Performance

| **Stage**          | **Accuracy** |
|---------------------|--------------|
| Pre-trained Model   | 69.3%        |
| Fine-tuned Model    | 95.7%        |

## Workflow

1. **Dataset Preparation**  
   - Selected 3,000 samples from the IMDB Movie Dataset.  
   - Preprocessed the text for training and testing.

2. **Pre-training Evaluation**  
   - Evaluated the pre-trained **Llama3.2-1B** model for sentiment classification.

3. **Fine-tuning the Model**  
   - Fine-tuned the model on the prepared dataset using the **Hugging Face Transformers** library.

4. **Post-training Evaluation**  
   - Evaluated the fine-tuned model, achieving significant performance improvement.
