动态规划是一种常用的解决问题的办法。它的主要作用是减少重复计算，
而不是给你解题带来启发。减少重复计算的办法是记录子问题的解而避免了
子问题的重复求解。使用动态规划，首先要做的是找到状态转移
方程。有了状态转移方程以后，递归解法自然就已经有了。
所谓状态转移方程，就是如何由子问题的解得到原问题解的一个过程。

至于怎么划分子问题，以及如何得到状态转移方程，我并没有找到什么有章可循
的办法。更多地靠直觉和经验吧。

通常在递归的数据结构上的问题，都可以用动态规划求解，如tree, graph,
array, string, list等。
