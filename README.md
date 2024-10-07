# Metro Rail Network Analysis using Social Network Analysis Techniques
This project aims to analyze the metro rail systems of four major cities—Kolkata, Delhi, Chennai, and Hyderabad—through a social network analysis perspective. The analysis evaluates metro networks using centrality measures such as:

## Degree Centrality: 
Identifies the most connected stations.
## Betweenness Centrality: 
Highlights critical stations frequently traversed by passengers.
## Closeness Centrality: 
Identifies stations closely connected to others in terms of distance.
## Eigenvector Centrality: 
Measures a station's influence based on its connectivity to other key stations.

In addition to these conventional measures, we introduced novel parameters:

1. Metro Topological Efficiency (MTE): Assesses the efficiency of the metro network in terms of information flow.

2. Node Occupying Probability (NOP): Quantifies a station's importance based on the number of routes passing through it, offering a realistic assessment of centrality.

3. Cost Adjustment Ratio (CA): Evaluates the robustness of the metro networks under random node failures.

Data Collection and Processing:
The dataset, consisting of metro line information, was collected via web scraping from the respective official metro websites and Wikipedia. The data was processed to create edge lists and convert station names into IDs for the application of the analysis.

## Key Findings:
The Delhi Metro system showed superior topological efficiency compared to other cities.
High betweenness centrality was observed at Rajiv Chowk in Delhi, while Esplanade was prominent in Kolkata for eigenvector and closeness centralities.
A comparison of NOP with degree centrality uncovered certain exceptions, where stations with high degree values did not lie on influential routes.
## Conclusion:
This analysis provides insights into the robustness and efficiency of metro systems, demonstrating that the New Delhi Metro network is topologically more efficient. The Node Occupying Probability (NOP) was effective in determining station importance and vulnerability under potential disruptions. The cost adjustment ratio highlighted each network’s tolerance to random node failures, informing network robustness strategies.
