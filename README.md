# GNN tutorials

<!-- After the first Zenodo release, paste the concept-DOI badge here (from zenodo.org → account → GitHub → this repo). It looks like:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX) -->

Hands-on companion notebooks to the review chapter *Machine Learning Techniques for Astrophysics and Cosmology: Graph Neural Networks* (C. K. Jespersen, Springer, to appear). Both notebooks run in the browser on Google Colab — no installation needed. Click a badge to launch.

| Notebook | What it covers | Launch |
| --- | --- | --- |
| [GNN tutorial](CRAQ_GNN_tutorial.ipynb) | A guided introduction to graph neural networks: build the graph, pass the messages, and explore how different inductive biases — embedded through the choice of layer and aggregation — change the performance and optimisation of the GNN. | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astrockragh/GNN_tutorials/blob/main/CRAQ_GNN_tutorial.ipynb) |
| [Galaxy–environment competition](CRAQ_galaxy_environment_competition.ipynb) | A competition-style exploration of the galaxy–environment connection: learn galaxy and halo properties from cosmic-web neighbourhood graphs built at linking lengths from 0.3 to 3 Mpc, following the exploration behind a published GNN analysis. | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astrockragh/GNN_tutorials/blob/main/CRAQ_galaxy_environment_competition.ipynb) |

## Run locally

```bash
git clone https://github.com/astrockragh/GNN_tutorials.git
pip install torch torch-geometric torch-scatter torch-sparse torch-cluster accelerate numpy matplotlib tqdm
```

On Colab the notebooks install their own dependencies in the first cell.

## Citing

If these notebooks feed into your research or teaching, please cite the review chapter:

> Jespersen, C. K., *Machine Learning Techniques for Astrophysics and Cosmology: Graph Neural Networks*, Springer (to appear).

A citable, versioned archive of this repository lives on Zenodo once the first release is cut — cite the concept DOI shown in the badge above.
