# Key insights
- Minimax AlphaBeta pruning only works when you sort Max Player's children nodes in descending order and Min Player's children nodes in ascending order.
- Minimax AlphaBeta pruning only starts pruning after you have ***at least*** visited all nodes at bottom-left branch

# How to visualise the tree in this Jupyter Notebook
Suppose you have a tree that look like: ![image](https://github.com/user-attachments/assets/2ed56087-97b6-4172-abda-605aab227e7b) <br />


In this notebook, it will be read as <br /> ![image](https://github.com/user-attachments/assets/696a4bef-a436-4f06-ab46-6b462cd04e63). <br />
Where the more indent, the deeper we get to the bottom nodes. <br />

Finally, the minimax function will give you the value for root node at the top.
