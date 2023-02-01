# Fortune_500_Director_Board_Network
In this repo, I analyze & visualize board connections among Fortune 500 corporations.

Key takeaways from this repo:
- understanding the significance of social networks
- creating social networks at different levels of analysis
- visualizing social network graphs

![Recording_of_graph](https://user-images.githubusercontent.com/116262236/216172387-1d0dee04-400e-4899-8adb-a3ec6197bcad.gif)

                                                                            


# Value of social networks
Researchers think of social networks as ['pipes and prisms'](https://www.jstor.org/stable/10.1086/323038). Social networks **aka pipes** enable people & organizations to access resources & information which influence their opportunities or [limitations](https://www.jstor.org/stable/2640283) and thus their behavior. Social connections **aka prisms** also affect how they perceive the world & vice versa. Social network analysis is a sytematic way to measure constructs like status which affect an organization's [exchange partners](https://www.jstor.org/stable/2393299#metadata_info_tab_contents). 

## The Data
This repo uses data on corporate board intelocks from 1998 to 2018. A board interlock occurs when a director sits on 2 or more boards. Thus, forming a connection (aka interlock) between them. Board interlocks are important because they affect the practices that companies [adopt](https://www.journals.uchicago.edu/doi/abs/10.1086/231170). 

This data is proprietary & comes from Boardex. It comprises of:
- 1,153 companies
- 15,367 individuals

The visualizations are based on:
- 773 nodes (companies)
- 1,368 edges (board interlocks)
- These board interlocks came from 5,538 corporate directors

# Methodology

## Key Characteristics of this particular network
- Non-directional
- Code is applicable for constructing social connectons 

## Practical applicatins for the code
1. Building inter-organizational network graphs based on individuals' actions
2. Visualizing a large network


