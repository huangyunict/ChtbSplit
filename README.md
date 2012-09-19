ChtbSplit
=========

The Penn Chinese Treebank Project provides annotated word segmentation, part-of-speech tagging, and constituency trees for Chinese.

The corpus Penn Chinese Treebank 6.0 (LDC2007T36) contains a file named "list-of-files.pdf".
This file includes a recommended data split for training, development and test datasets.
Since it is a PDF file, however, it is not easy to extract the file IDs from it.
I manually copy the file IDs to separated plain text files.
These files may facilitate further data preparing process.

ctb_v6.split.txt: the data split information
ctb_v6.trn.idx  : the file indices for training set
ctb_v6.dev.idx  : the file indices for development set
ctb_v6.tst.idx  : the file indices for test set

