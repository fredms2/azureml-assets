| | |
| -- | -- |
| Score range | Float [0-1]: higher means better quality. |
| What is this metric? | ROUGE (Recall-Oriented Understudy for Gisting Evaluation) is a set of metrics used to evaluate automatic summarization and machine translation. It measures the overlap between generated text and reference summaries. ROUGE focuses on recall-oriented measures to assess how well the generated text covers the reference text. The ROUGE score is composed of precision, recall, and F1 score. |
| How does it work? | The ROUGE score evaluates the similarity between the generated text and reference text based on n-gram overlap, including ROUGE-N (unigram, bigram, etc.), and ROUGE-L (longest common subsequence). It calculates precision, recall, and F1 scores to capture how well the generated text matches the reference text. Rouge type options are "rouge1" (Unigram overlap), "rouge2" (Bigram overlap), "rouge3" (Trigram overlap),  "rouge4" (4-gram overlap), "rouge5" (5-gram overlap), "rougeL" (L-graph overlap) |
| When to use it? | The recommended scenario is Natural Language Processing (NLP) tasks. Text summarization and document comparison are among the recommended use cases for ROUGE, especially when focusing on recall and the ability to capture relevant information from the reference text. |
| What does it need as input? | Response, Ground Truth |
