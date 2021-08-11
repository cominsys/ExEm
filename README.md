# ExEm: Expert embedding using dominating set theory with deep learning approaches

Code repository of the ExEm: Expert Embedding using dominating set theory with deep learning approaches

Article:
https://arxiv.org/abs/2001.08503

Published Journal Version:
https://doi.org/10.1016/j.eswa.2021.114913

## Article's Abstract:
A collaborative network is a social network that is comprised of experts who cooperate with each other to fulfill a special goal. Analyzing this network yields meaningful information about the expertise of these experts and their subject areas. To perform the analysis, graph embedding techniques have emerged as an effective and promising tool. Graph embedding attempts to represent graph nodes as low-dimensional vectors. In this paper, we propose a graph embedding method, called ExEm, that uses dominating-set theory and deep learning approaches to capture node representations. ExEm finds dominating nodes of the collaborative network and constructs intelligent random walks that comprise of at least two dominating nodes. One dominating node should appear at the beginning of each path sampled to characterize the local neighborhoods. Moreover, the second dominating node reflects the global structure information. To learn the node embeddings, ExEm exploits three embedding methods including Word2vec, fastText and the concatenation of these two. The final result is the low-dimensional vectors of experts, called expert embeddings. The extracted expert embeddings can be applied to many applications. In order to extend these embeddings into the expert recommendation system, we introduce a novel strategy that uses expert vectors to calculate experts’ scores and recommend experts. At the end, we conduct extensive experiments to validate the effectiveness of ExEm through assessing its performance over multi-label classification, link prediction, and recommendation tasks on common datasets and our collected data formed by crawling the vast author Scopus profiles. The experiments show that ExEm outperforms the baselines especially in dense networks.

## Highlights
* A novel graph embedding using dominating-set theory and deep learning is proposed.
* A strategy to calculate experts’ scores based on expert embeddings is proposed.
* We present data for a co-author network by crawling author profiles from Scopus.

Cite:
```bib
@article{nikzad2021exem,
  title={ExEm: Expert embedding using dominating set theory with deep learning approaches},
  author={Nikzad-Khasmakhi, Narjes and Balafar, Mohammadali and Feizi-Derakhshi, Mohammad-Reza and Motamed, Cina},
  journal={Expert Systems with Applications},
  volume={177},
  pages={114913},
  year={2021},
  doi={10.1016/j.eswa.2021.114913},
  publisher={Elsevier}
}
