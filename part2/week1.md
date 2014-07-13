Week \#1
===========

Application: Internet Routing
-----------------------------
part2的主要内容:  
1. 贪婪算法  
2. 动态规划  

图算法应用的三个实例:  
1. internet, 路由器-主机网络  
2. websites, hyperlink引用网络  
3. 社交网络  

图中最短路径的三个算法:  
1. Dijkstra (但是要知道整个网络的路由器的信息，不可能！)  
2. Bellman-ford  


Application: Sequence Alignment
----------------------------
计算两个字符串的相似度，如果遍历所有情况很复杂不可能完成，需要动态规划(Needleman–Wunsch algorithm)


Introduction to Greedy Algorithm
-------------------------------
design pattern:  
1. divide and conquer (part 1)  
2. randomized algorithms (part 1)  
3. greedy algorithm (part 2)  
4. dynamic programming (part 2)

贪婪算法优缺点：  
1. 容易实现(显然的)  
2. 容易分析时间复杂度(conquer and devide 的时间往往不确定，比如quicksort algo)  
3. 正确性难以衡量(局部最优不一定全局最优), 比如Dijkstra在所有边非负的时候是正确的，若有负边则是错的(视频中给出了例子)

证明正确性的方法: (saying coming next, 不懂。。)  
1. induction  
2. exchange argument  
3. other methods whatever works (证明贪婪算法正确没有固定模式，it's art rather than science)
