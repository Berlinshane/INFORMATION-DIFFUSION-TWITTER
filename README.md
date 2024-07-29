A Comparative Analysis of Social Network Epidemic Models


Introduction:

In recent years, the ability to predict the propagation of information within networks has become increasingly crucial,
particularly in the context of online social media platforms where the dissemination of information can significantly impact social
events. Researchers employ diverse methods, including network mapping and analysis, data mining, and machine learning algorithms, 
to investigate social networks and their connections.These methods help identify key nodes and influential elements
within a network and comprehend the underlying dynamics governing knowledge dissemination. This research focuses on
applying three epidemic models, namely SI, SIS, and SIR, to social network datasets at varying levels of complexity, ranging from small to medium and complex networks. The paper
delves into the impact of centrality measures such as degree, betweenness and eigen vector and presents the comparison of
the models. It concludes by recommending the most suitable social network epidemic model and the centrality measure for
enhancing information diffusion within the network, offering potential applications for businesses in digital marketing and
advertising.

Analysis:

Information is diffused in the network by selecting the start node as the different high centrality measures node. Number
of iterations required to reach the certain set of population are recorded.


Case 1 - Degree Centrality: The SI model initially shows a relatively quick spread.This suggests a rapid initial diffusion
of information from the highest degree centrality node. But for 100% of nodes takes significantly more iterations (180). So it
can be said that as more nodes become infected it becomes increasingly challenging for the information to reach other
nodes. In contrast to SI model, SIS model takes nil iterations to reach 40%, 60%, 80% and even 100% of nodes. This suggests
that the nodes tend to lose the information quickly or revert to a susceptible state. SIR model is very similar to SIS. It
takes 33 iterations to reach 40% of nodes and then only nil. This indicates a slow initial spread and an incomplete diffusion
process. These interpretations suggest that while the highest degree centrality node serves as an effective initial node,the
choice of spreading model should be SI.Both SIS and SIR looks similar it reverts from infection state.

Case 2 - Betweenness Centrality: In contrast to degree centrality, the number of iterations increases substantially as
the target percentage of nodes increases in case of SI model.It took 200 iterations to reach the entire network. The SIS
model indicated a slower spread initially taking 100 iterations to reach 20% of nodes itself. It indicates its inability to reach
remaining nodes. Similar to SIS model, the SIR model also showed limitations in spreading information from the highest
betweenness centrality node. It took 20 iterations to reach 20% of nodes and then it could not reach other part of network. So,
betweenness centrality’s effectiveness seems limited across all diffusion models, especially for higher percent of nodes. SI
facilitates initial quick spread; SIS and SIR show limitations in spreading information beyond certain percentage.

Case 3 - Eigenvector Centrality: It is clearly evident that there were increasing iterations in the SI model. This was
gradual but continuous increase in the effort required to spread information across a larger portion of the network from the
node with highest eigenvector centrality. SIS model took 350 iterations to reach 20% of nodes and 580 iterations to reach
50% of nodes. It recorded its inability to reach the remaining part of the network. SIR model indicated moderate iterations
which took lesser number of iterations than SIS model. It took only 30 iterations to reach 20% of nodes and only 36
iterations to each 50% of nodes. Similar to SIS model, it was not able to reach remaining 50% nodes, in spite of increase
in iterations. The node with the highest eigenvector centrality initially facilitates effective information spread, especially in
SI and SIR models. While the SI model showcases a more gradual increase in iterations, the SIS and SIR models hit
limitations at earlier reach of nodes and struggle to spread information efficiently across larger portions of the network.


