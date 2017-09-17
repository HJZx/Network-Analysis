# 二分网络转单顶点网络

基本处理：使用Python下的网络分析专用模块networkx，完成数据的文件读取、数据处理和文件输出。

准备材料：待处理的二分网络边列表(csv)，包含两列信息，分别储存演员/电影信息，每行是演员与电影的对应关系（出演）。

做法：
1.	在当前文件夹下，准备Python脚本和二分网络边列表，即 bipartite_network.py 和 edgelsit.csv。

2.	在Terminal中，进入到当前文件夹下，执行bipartite_network文件，按照体术输入边列表文件名，案例中输入edgelist.csv。

3.	得到"Finished!"反馈信息后，程序完成二分网络到单节点网络的转换，并在当前文件夹下生成四个文件，分别是两个网络的nodelist和edgelist。
