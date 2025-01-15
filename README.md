# LLM-eval
Evalutation of LLMs in production

## Primary Goals for Evaluating LLM in Production
The primary goals for evaluating the LLM in production include:
- Latency
- Accuracy
- Bias detection

## Metrics to Measure Goals
To measure these goals, the following metrics will be used:
- BLEU score
- Response time
- Hallucination rate

## Baseline Thresholds for Metrics
The baseline thresholds for these metrics are established as follows:
- BLEU score: 0.7
- Response time: 200ms
- Hallucination rate: 5%

## Datasets Used for Evaluation
The datasets used for evaluating the LLM include open-domain datasets, task-specific datasets, and edge cases. These datasets are curated to cover a wide range of scenarios and ensure comprehensive evaluation.

## Preprocessing Steps
The datasets are preprocessed to ensure consistency and relevance. The preprocessing steps include:
- Handling missing values
- Removing duplicates
- Normalizing numerical columns
- Encoding categorical columns

## Subsets Created for Targeted Testing
To perform targeted testing, the following subsets of the dataset are created:
- Stress Test Dataset: A subset containing 10% of the data for stress testing.
- Adversarial Queries Dataset: A subset containing 5% of the data for adversarial queries.
