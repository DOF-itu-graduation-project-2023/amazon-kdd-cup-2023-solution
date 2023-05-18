# amazon-kdd-cup-2023-solution

1. run 'preprocess-session-test-task2-data.ipynb' for each locale
2. run 'preprocess-session-train-data.ipynb' for each locale
3. run 'w2v-session-embedding-generation.ipynb' for each locale and generate embeddings (you may change Window Size)
4. run 'preprocess-product-data.ipynb' for each locale (you may change alpha value for title en desc composition)
5. run 'embedding-composition.ipynb' for each locale (you may change alpha value for embedding composition)

Embeddings are created with these steps! After that you can train SR-GNN for each locale
