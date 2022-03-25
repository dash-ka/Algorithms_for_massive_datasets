# Algorithms_for_massive_datasets

In the project we perform market basket analysis on the «Ukraine Conflict Twitter» dataset, published on Kaggle and released under the CC-BY-SA 4.0 license.
First we represent the dataset as a sequence of baskets of items, by tokenizing single tweets. Next, we implement the Savasere, Omiecinski, and Navathe algorithm to mine frequent itemsets. The SON algorithm lends itself well to a parallel-computing environment, and allow us to exploit MapReduce framework for processing large-scale data.
The report explaining the details about implementation and results is attached in the pdf file. The notebook with code is available at 
