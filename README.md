# Algorithms_for_massive_datasets

In the project we perform market basket analysis on the «Ukraine Conflict Twitter» dataset, 
published on Kaggle and released under the CC-BY-SA 4.0 license.
First, we represent the dataset as a sequence of baskets of items, by tokenizing single tweets.
Next, we implement the Savasere, Omiecinski, and Navathe algorithm to mine frequent itemsets. 
The SON algorithm lends itself well to a parallel-computing environment, 
thus allowing us to exploit Map Reduce framework for processing large-scale data.
All the details concerning implementation and results are covered in the report attached as pdf file within the repository.
The notebook with code is available at
<a href="https://colab.research.google.com/github/dash-ka/Algorithms_for_massive_datasets/blob/master/SON_frequent_itemsets.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
