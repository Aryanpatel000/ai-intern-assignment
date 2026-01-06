## Task 1 – Yelp Rating Prediction via Prompting

### Dataset
Yelp Reviews Dataset (Kaggle)

### Objective
Predict 1–5 star ratings from review text using LLM prompting.

### LLM Used
Gemini 1.5 Flash (Free Tier)

### Prompting Approaches
Prompt v1: Basic instruction-based prompt
Prompt v2: Structured JSON-enforced prompt
Prompt v3: Few-shot + strict output format prompt

### Evaluation Metrics
Accuracy (Predicted vs Actual Stars)
JSON Validity Rate

### Notes
Evaluation performed on a sampled subset due to API rate limits.
Retry and graceful failure handling implemented.
