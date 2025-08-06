**Document:** A row in your dataset or an entry in a list, for example
**Topic Modelling:** Involves scanning each document to identify pattersn - similar documents are then grouped together. This is an example of unsurpervised learning, more specifically, clustering

## How it works

1. Look for patterns of co-occurring words
    - “goal” and “score” appear together often → probably related
    - “oven” and “recipe” appear together often → another relation
2. Group these patterns into topics
    - The model says: “Words A, B, C belong to Topic 1; Words X, Y, Z belong to Topic 2…”
3. Give each document a mix of topics
    - A sports article about a cooking show might be:
    - 70% Sports, 30% Cooking

## Usecases

- News categorization:	Grouping news into politics, sports, etc.
- Customer feedback:	Discovering main themes in survey comments
- Research papers:	Finding common research areas automatically
- Social media monitoring:	Spotting trending discussion topics

## Two common topic modelling algorithms

- Latent Dirichlet Allocation (LDA)
- Latent Semantic Analysis (LSA).