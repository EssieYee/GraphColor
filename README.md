Group 2: Graph Coloring

• Graph Coloring：对图的顶点着色，相邻顶点不同颜色，给出一种着色方案。假设可用color数比实际需要的最小数大很多。
• 计算方法
每个顶点记录自己的color，初始为-1
Superstep = 0，顶点V0着色color=0，向邻居发送颜色编号
接下来的 superstep 中，顶点收到消息后，统计邻居顶点的颜色，随机选  择一个与之不冲突的颜色号着色
• 输入：无向图（有成对的有向边），命令行：V0，总color数•
输出：
顶点id : 颜色号顶点id : 颜色号…
