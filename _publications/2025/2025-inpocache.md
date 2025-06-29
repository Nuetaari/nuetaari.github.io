---
title:          "InpoCache: Indexed Prompt Caching for Efficient LLM Query Serving"
date:           2025-06-24
selected:       true
abstract: >-
  Large Language Models (LLMs) are the center of many modern AI applications, such as chatbots and virtual assistants. However, their use often incurs high latency and computational costs due to redundant API calls for semantically similar queries. To address this inefficiency, we propose InpoCache, an indexed prompt caching system designed to reduce the lookup latency of LLM responses using lightweight indexing schemes, including binary search trees (BSTs) by query length, top-n k-means clustering based on embeddings, and K-D trees. Experimental results across multiple datasets demonstrate that the best-performing method of InpoCache, that is the K-D-tree based indexing, consistently records the lowest average latency while maintaining high accuracy with no false positive results, that is, 93.83 ms with 97.33% accuracy on a dataset with 1503 entries. Furthermore, compared to unindexed sequential search, all proposed indexing schemes significantly reduce lookup time while maintaining a high accuracy, no lower than 90%.
cover:          /assets/images/covers/image.png
links:
  Paper: https://informatika.stei.itb.ac.id/~rinaldi.munir/Stmik/2024-2025/Makalah2025/Makalah-IF2211-Strategi-Algoritma-2025%20(100).pdf
  Code: https://github.com/Nuetaari/InpoCache
---