# Transformer




# The Dataset
https://www.kaggle.com/datasets/dhruvildave/en-fr-translation-dataset

- This data set was 8 GB big! i could not read it on my measely 16 GB RAM laptop and so i chose to split it into chunks of 1 Million lines.


I tried to write my own tokenizer. i have learnt how Byte Pair encoding works.. but it is too slow!! very very slow! i figured it was good enough that i learned how it works that i chose to build a custom tokenizer from a library

- The vocabulary size was 30k by default and that was too big! 
- I tried 8192 (2^13) vocabulary size 