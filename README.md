# Introduction

## Assignment Instructions
In this assignment, you will use Spark to identify the most similar document of a given document. Your program will be given two items as input-

1. A folder containing all the documents. This folder may or may not have subfolders. In any case, your program should be general enough to compare against all the documents in that first folder or within the subfolders.

2. A single text document. 

Your program should print the names of the 5-most similar documents to the given document. 

Implementation

1. You should use Google Colab and Spark (pyspark) to do this project. You can use Java or Scala implementation of Spark as well in case you aren't familiar with Python.

2. For similarity calculation, implement LSH with MinHash (Jaccard similarity). Use the MMDS book as a reference for the MinHash and LSH. Take a look at W3 lecture for LSH and W4 lecture for Spark.

3. Spark provides packages to do Minhash & LSH. You can use that. But if you implement your own LSH and MinHash, there are 10 Bonus points.

Deliverables

1. Your Google Colab Notebook.


## Solution
Repository contains Google Colab file which implements Jaccard Distance using MinHash package from PySpark Library.
Code implements installing of PySpark on Google Colab with implementation of string formatting, list manipulation and MinHash implementation using Pythong and PySpark.

### Assumptions
Input file is assumed to be taken as a .zip archive of text files (1-level of sub-folder verified) and a reference text file.

### Output
Provides a table of Jaccard Distance scores calculated using MinHash implementation ordered in ascending value of Jaccard Distance and showing top 5 matching documents as per assingment guidelines.
