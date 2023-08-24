# Information_Retrival_System (CS657A: Information Retrieval)

## Library needed
1. re
2. os
3. sys
4. nltk
5. numpy
6. pickle
7. collections

## How to run code
1. To create index - ```python3 indexing.py``` - index is saved in index and info files and can be used directly.
2. To search query - ```python3 main.py``` path - path of query.txt file
3. To calculate score of three system - python3 mAP.py path - path of relevance file in qrels format.
4. Makefile - To install package run ```make```
 - To make index run ```make index```
 - To make search querys from query.txt run ```make run```
 - To remove main.py output files 3 .txt file run ```make clean```
