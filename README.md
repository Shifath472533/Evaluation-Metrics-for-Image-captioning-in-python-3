### Evaluation-Metrics-for-Image-captioning-in-python-3

I have seen many people who struggle to evalute the quality of captions using evaluation metrics in image captioning. <br>
So I have gathered almost all the metrics available for it in **Calculating_Metrics.ipynb** implementing in **python 3**. <br>
So use it and goodluck :)<br>


### Available metrics:
------------------
 - BLEU-1
 - BLEU-2
 - BLEU-3
 - BLEU-4
 - METEOR
 - ROUGE
 - CIDER
 - SPICE
 - gleu
 - SkipThoughtCS
 - EmbeddingAverageCosineSimilarity
 - VectorExtremaCosineSimilarity
 - GreedyMatchingScore

### Used Libraries:
-------------------
 - pycocoevalcap
 - ngEval
 - nltk


### Examples:
---------
- gts.json   -> this file contains example captions with image ids
- res.json   -> this file contains references for the example captions
