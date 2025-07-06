## Airline Feedback Sentiment Classifier (watsonx.ai)

This project uses IBM watsonx.ai's FLAN-UL2 foundation model to classify airline passenger feedback into three sentiment categories:
Positive, Neutral, or Negative, using few-shot prompt-based learning.

## Files Included
- `airline_feedback_train.csv`
- `airline_feedback_test.csv`

## What It Does
- Loads airline feedback data from IBM Cloud Object Storage
- Uses prompt engineering to guide the foundation model
- Predicts the sentiment (positive, neutral, negative) for each review text

## Model Used
FLAN-UL2 from IBM watsonx.ai

## How to Use
1.Upload your CSV files (airline_feedback_train.csv and airline_feedback_test.csv) to an IBM Cloud Object Storage bucket.

2.Provide your IBM Cloud:

  - API key
         
  - Project ID
         
  - Bucket name
         
3.Run the notebook in [watsonx.ai](https://dataplatform.cloud.ibm.com) to classify airline passenger feedback as positive, neutral, or negative using the few-shot prompt and display predictions.
