# Source Code Modelling using LSTM

An LSTM (based on https://arxiv.org/pdf/1608.02715.pdf) was trained to predict Java source code tokens

SCRNN.net - checkpoint of a trained model using Pytorch. A perplexity equal to 4.95 was reached. The model was used for Java source code features extraction in code smells classification problem (https://github.com/D-a-r-e-k/Code-Smells-Detection)

code_corpus - a dataset of sequences of code tokens formed based on Java Github Corpus (http://groups.inf.ed.ac.uk/cup/javaGithub/)
dictionary - only 1K most popular code tokens were left in code_corpus, other were changed with <unk>
