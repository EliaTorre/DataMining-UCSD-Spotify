<h1 align="center">
Spotify Song Popularity & Content-Based Recommendation System</h1>
<div align="center">

  <a href="https://www.linkedin.com/in/eliatorre/">Elia Torre</a>
  <p><a href="https://datascience.ucsd.edu/">Halıcıoğlu Data Science Institute</a>, UC San Diego, La Jolla, CA</p>
</div>


## Highlights and Contributions


>**<p align="justify"> Abstract:** *This repository presents the research undertaken in the Final Project for DSC190 - Intro- duction to Data Mining course. The purpose of this project is dual. In the first part of the associated notebook (Github Link), Spotify Songs Dataset will be explored with the aim of developing and fine-tuning two Regression Models (XGBRegressor and Random- ForestRegressor) to predict the popularity of a song and evaluating their performance against a baseline model (LinearRegression). In a second section, in light of a deeper understanding of the dataset and its characteristics, we delve into the construction of a Content-Based Recommendation System which relies on "vectorization" and Cosine Similarity. In this second part of the project, the user can interact with the system to receive song recommendations starting from one of its Spotify playlists.*

### Main Contributions
1. **Graph coarsening via spectral clustering**: We propose a scheme to coarsen graph representation via spectral clustering with the relaxed formulation of the MinCUT problem, as presented in the [paper](https://arxiv.org/abs/1907.00481) from Bianchi et. al. We observe the structural patterns uncovered by SC reveal which long-range virtual connections should be made.
2. **New connections learned by a heterogeneous network**: We create an intra-cluster connection with a virtual node, and learn the new relationship as a graph indepdenent of the original graph. A heterogeneous convolutional network is trained on these separate relations, further coarsening the representations. On our set of ablation studies, and after hyperparameter tuning, Graph-HSCN out-performs the traditional message-passing architectures by up to 10 percent, achieving metrics similar to those of SAN while reducing the time complexity.

## Getting Started

### Prerequisites
To set up the environment and install all dependencies, run `make env`. The `logs` and `datasets` directories will be created automatically at the project level.
  
### `.devcontainers` Support
TODO
### Running with CLI
TODO
### Running in Prefect UI
TODO

<hr/>

## Hyperparameter Tuning & Results
TODO

<hr/>

## Contact
Feel free to open an issue on this repository or e-mail adunning@ucsd.edu.
  
## Acknowledgements
The code in this project is heavily adapted and modified from the following repositories:
1. [Long Range Graph Benchmark](https://github.com/vijaydwivedi75/lrgb)
2. [torch_geometric GraphGym](https://github.com/pyg-team/pytorch_geometric/tree/master/graphgym)
3. [Hierarchical Graph Net](https://github.com/rampasek/HGNet)
