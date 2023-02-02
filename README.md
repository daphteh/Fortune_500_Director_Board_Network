# Fortune_500_Director_Board_Network
In this repo, I analyze & visualize board connections among Fortune 500 corporations.

Key takeaways from this repo:
- understanding the significance of social networks
- creating social networks at different levels of analysis
- visualizing social network graphs

![Recording_of_graph](https://user-images.githubusercontent.com/116262236/216172387-1d0dee04-400e-4899-8adb-a3ec6197bcad.gif)
                                                                            
# Value of Social Networks
Researchers think of social networks as ['pipes and prisms'](https://www.jstor.org/stable/10.1086/323038). Social networks **aka pipes** enable people & organizations to access resources & information which influence their opportunities or [limitations](https://www.jstor.org/stable/2640283) and thus their behavior. Social connections **aka prisms** also affect how they perceive the world & vice versa. Social network analysis is a sytematic way to measure constructs like status which affect an organization's [exchange partners](https://www.jstor.org/stable/2393299#metadata_info_tab_contents). 

Social network analysis can be used to discern:
- Power dynamics
- Sources of knowledge
- Communities of influence
- How information [spreads](https://journals.sagepub.com/doi/abs/10.1177/0003122416629611) <- check out my paper with implications on how the spread of negative information affects associated organizations 

<details>
<summary> Social networks comprise of: nodes (these are the entities that are connected to each other) and edges (relationships between nodes) </summary>
  <br>
  <p> Examples of nodes: </p>
  <p> companies </p>
  <p> universities </p>
  <p> institutions </p>
  <p> departments within an organization</p>
  <p> people </p>
  <p> patents </p>
  <p> Edges can reflect characteristics like: </p>
  <p> type of interpersonal relationships: authority, advice giving-solicitation, teacher-student, friendship, romance, familial </p>
  <p> types of interorganizational relationships: alliances, partnership </p>
  <p> Strength of the connections </p>
  <p> Direction of resource flow: uni-directional / bi-directional </p>
</details>

# Practical Applications
- Identifying change agents within an organization --> important for implementing new policies
- Understanding relationships between banks and their clients
- Discerning entities vulnerable to fraud
- Interpreting someone's network & expertise --> useful for hiring sales people / recruiters 
- Analyzing the patents that affect new product development
  
# This Repo  
## The Data
This repo uses data on corporate board intelocks in 2018. A board interlock occurs when a director sits on 2 or more boards. Thus, forming a connection (aka interlock) between them. Board interlocks are important because they affect the practices that companies [adopt](https://www.journals.uchicago.edu/doi/abs/10.1086/231170) as well as [power](https://global.oup.com/academic/product/managed-by-the-markets-9780199216611?cc=ch&lang=en&) & [governance](https://www.jstor.org/stable/257831).  

This data is proprietary & comes from Boardex. It comprises of:
- 773 nodes (companies)
- 1,368 edges (board interlocks)
- These board interlocks are based on 5,538 corporate directors

## The Code
This is useful for:
- Building aggregated network graphs built on individuals' actions (e.g. connections between universities & firms based on where students work post-graduation)
- Visualizing a large network

Key characteristics of the graph:
- non-directional
- interactive and dynamic - you can zoom into the nodes, click on them to see additional information & drag them
- customizable
