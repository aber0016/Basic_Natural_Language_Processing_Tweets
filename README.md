# Natural_Language_Processing_Tweets

Text documents, such as crawled web data, are usually comprised of topically coherent text data, which within each topically coherent data, one would expect that the word usage demonstrates more consistent lexical distributions than that across data-set. A linear partition of texts into topic segments can be used for text analysis tasks, such as passage retrieval in IR (information retrieval), document summarization, recommender systems, and learning-to-rank methods.

In order to perform such text analysis tasks, this project firstly extracts text data from tweets saved in an XML format. Seconldy, a set of text pre-processing steps are undertaken including:

1. Generate the corpus vocabulary with the same structure as sample_vocab.txt. Please note that the vocabulary must be sorted alphabetically.

2. For each day (i.e., sheet in your excel file), calculate the top 100 frequent unigram and top-100 frequent bigrams according to the structure of the sample_100uni.txt and sample_100bi.txt. If you have less than 100 bigrams for a particular day, just include the top-n bigrams for that day (n<100).

3. Generate the sparse representation (i.e., doc-term matrix) of the excel file according to the structure of the sample_countVec.txt
