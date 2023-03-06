# Deep Cross-Modal Hashing
## Pre work
1. ANN(Approximate Nearest Neighbour)
   又名随机投影森林  
- 本质是寻找近邻样本
- 超平面上任选一种维度，按照该维度上的度量选取中电划分超平面，对每一个维度依次操作，直到满足某种分割条件（例如每个子区域内部的点数都不超过k）
- annoy算法