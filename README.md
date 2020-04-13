# linguistic-parallelism-identification (inter-sentence-level)
This is a sister project of inner-sentence level parallelism identification (see: https://github.com/JYWangGeneCosmo/linguistic-parallelism-identification-inner-sentence-level-)

This project focus on automatic identification of inter-sentence level parallelism and takes not only lexical and syntactic features, but also semantic features (with NRC-VAD Sentiment Lexicon) into account. The guidelines and the corresponding project report are uploaded in PDF format. The .csv file is the training/test dataset and .ipynb file is the python script (including feature engineering process) for this project.

## Dataset
Both parallelism identification projects employed American Inaugural Speeches to establish the training data.
Unlike the project for inner-sentence level parallelism which focuses more on grammatical parallelism, the guideline for establishing the training data for this project pays more attention to rhetoric parallelism.

## Performance
The cross-validated F1-score for parallelism class has reached 0.8902, which is higher than the best performance of the previous sister project for inner-sentence level parallelism (0.851).
