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

## Sample Test Set
The sample test set includes the following components:
- Input queries
- Relevant source documents/passages
- Expected/reference answers
- Query-document relevance judgments
- Query types (factoid, open-ended, etc.)

## Improvements to Ground Truth Dataset
The ground truth dataset has been improved by adding more diverse and comprehensive input queries, relevant source documents/passages, and expected/reference answers. Additionally, the query-document relevance judgments and query types have been refined to ensure better evaluation of the LLMs.
