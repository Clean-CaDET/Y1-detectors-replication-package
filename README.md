# Y1-detectors-replication-package

This is a replication package for the paper "Automatic detection of Long Method and God Class code smells through neural source code embeddings", submitted for consideration in _Expert Systems with Applications_ journal. 

In our experiments we used the MLCQ dataset:
_Madeyski, L. and Lewowski, T., 2020. MLCQ: Industry-relevant code smell data set. In Proceedings of the Evaluation and Assessment in Software Engineering (pp. 342-347)._,
publicly available at https://zenodo.org/record/3590102#.YPkzL-gzY2w. 

Upon article publishing, this repository will contain the following files:
1. MLCQ_experiment_setup.xlsx - the specification of our experimental setup. For each sample, we provide its label used in the experiment and whether the sample belonged to the training or the test dataset.
2. MLCQ_processed_metrics.xlsx - the processed version of the MLCQ dataset: the vector of source code metrics we extracted for each code sample.
3. MLCQ_processed_CuBERT.xlsx - the processed version of the MLCQ dataset: CuBERT embedding vector obtained for each code sample.
4. MLCQ_processed_code2vec.xlsx - the processed version of the MLCQ dataset: code2vec embedding vector obtained for each code sample.
5. MLCQ_processed_code2seq.xlsx - the processed version of the MLCQ dataset: code2seq embedding vector obtained for each code sample.
6. MLCQ_heuristics.xlsx - the results of applying metric-base heuristic detectors: for each heuristics we note whether the heuristic labeled the code sample as a code smell or as a non-smell.
