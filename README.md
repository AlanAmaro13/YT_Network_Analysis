
# Youtube Network Analysis

Welcome back! In this repository you will find a complete analysis based on Network Science/Applied Graph Theory over the Youtube's Social Network. 

## Index:
* Description
* Libraries
* Network Load
* General Properties of the Network
* Centrality Metrics
* Degree Distribution
* Interpretation of the Results
* Comparison with a Random Network
* Comparison wih a Scale-Free Network
* Diffusion Process: Spread of a Disease:
    * Random Vacunation
    * Hubs Vacunation 
* Conclusions

![Logo](https://github.com/AlanAmaro13/YT_Network_Analysis/blob/main/PNGofMiniature.png)

# Videos Explaining the Analysis:
All of the sections described here are explained in a playlist of YouTube videos, which are available in [Analysis Videos]()

# Spread of the Disease: 
The Spread-of-Disease Videos are avaible in the next [Playlist]()


# Conclusions 

* The YT network has approximately 1 million nodes with about 3 million links, which are interpreted as relationships between the network's users.

* The average degree of the network is 5.27, with an expected clustering value of 8e-2

* The network's diameter for the first 5,000 nodes is 5, while the reported overall value is 20.

* The closeness metric suggests that users form communities sparsely and consistently, with slightly oscillating behavior among users. The betweenness metric indicates the presence of hubs within the network, as there are users with high betweenness values, while the average is almost negligible.

* The degree distribution in a logarithmic scale suggests the presence of scale independence within the network.

* The network does not satisfy the small-world property. Although it has a small diameter relative to the number of nodes, it does not exhibit a high clustering coefficient.

* The network is not modelable using the Erdős-Rényi (ER) model, as the clustering coefficient and the associated probability differ by four orders of magnitude, and the degree probability distribution does not fit the expected Poisson curve.

* The network exhibits scale independence, with the degree probability distribution following a power law with alpha = 2.48 and k-min = 206.

* The epidemic diffusion modeling process suggests that random vaccination is ineffective, as it requires vaccinating 90% of the population. However, vaccinating hubs, which represent 0.2% of the population, achieves the same result.

## Acknowledgements

 - [Curso de Ciencia de Redes. Betancourt, F. García, L. 2023](https://curso-redes-f-ciencias-unam.github.io/ciencia-de-redes/matematicas_de_las_redes/matematicas_de_las_redes/presentacion.html)

## Feedback

If you have any feedback, please reach out to us at alan_amaro@ciencias.unam.mx

