# Detection of Counterfactual Statements using semantic search

This is a simple fun project to detect counterfactual statements.

## What is Counterfactual Statements?
- Counterfactual Statements are speculative statements about events or situations that did not actually happen but could have occurred under different circumstances. These statements are hypothetical and typically begin with phrases like "If only" or "What if".
More details about the Counterfactual Statements can be found here: [Amazon's Counterfactual Dataset](https://www.amazon.science/blog/amazon-releases-dataset-to-help-detect-counterfactual-phrases).

## Datset used?
- For this project Amazon's Counterfactual Dataset will be used. It consists of two main columns, the first one being the actual product review by the customers and the second column will be the flag is_counterfactual with 1 being the statement is counterfactual in nature and 0 meaning the statement is not counterfactual.
<img src="https://github.com/akash6murali/semantic-search/blob/main/assets/df.png" weight="20%">

## tokenizer and pretrained model used to extract the text embeddings?
- Using the BGE model which is one of top performing model in Massive Text Embedding Benchmark (MTEB) Leaderboard.
- has the max embedding dimension of 768 and max tokens of 512, memory usage of 0.41gb with fp32 precision.

## Code and Results?
- Refer the **semantic_search.ipynb** notebook for detail code and results. 
