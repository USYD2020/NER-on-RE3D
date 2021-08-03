# NER-on-RE3D-dataset

# Background
This project uses PART OF the re3d dataset from Defense Science and Technology Laboratory, U.K., which focuses on named entity extraction relevant to somebody operating in the role of a defence and security intelligent analyst. Four files (train, val, test) are provided as follows:

1. train.csv - the training set
2. val.csv - the validation set
3. test_without_labels.csv - the test set
4. sample.csv

Please note that only PART of the original re3d dataset is used (in order to reduce the training time) so one should use the GIVEN train.csv, val.csv, test_without_labels.csv. (not the same as the original dataset from the official website). The given data is based on IOB embedding. One can also check the sample submission (sample.csv) to compare with your own result.

# Abstract
This project works on implementing a Bi-LSTM CTF model with attention strategies to solve a Named Entity Recognition (NER) task for the defense corpus. Input embed- dings benefits from word level information and Part-of-Speech (PoS) labels. Our work is the first to experiment bidirectional LSTM (BI-LSTM) for the NER task. Attention is then applied but does not show significant improvement. Conditional Random Field (CRF) layer is extended and shows that it could capture dependencies between labels and improves the performance of NER model. Our system is commendable on the RE3D dataset and shows a significant performance improvement than a baseline model.
