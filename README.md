# Koala Evaluation Set

We release the test set we used for doing human evaluation of our Koala models.

This test-set consists of 180 queries that we source from publicly available user-written language model prompts. 
In order to mitigate test-set leakage, we filter out queries that have inter-bleu scores greater than 20% with our training set. 
Additionally, we remove non-English and coding-related prompts, since responses to these queries cannot be reliably reviewed by our pool of human raters. 
We release our test-set for academic use and future benchmarking of models here.

**Please do not use this test set for training purposes**
