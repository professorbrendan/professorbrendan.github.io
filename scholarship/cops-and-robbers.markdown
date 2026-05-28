---
layout: page
permalink: /Scholarship/Cops-and-Robbers/
---

# Computational Cops and Robbers

**Cops and Robbers** is a pursuit-evasion game played on graphs. A team of cops chooses starting vertices, then a robber chooses a starting vertex. The players alternate turns by moving along edges of the graph, and the cops win if one of them lands on the robber.

This project studies the game computationally, with a focus on cop number, capture time, and optimal strategies. I am particularly interested in the the "lazy cops" variant of the game where only one cop may move per turn, and I've recently focused on graphs formed via Cartesian and strong products of simpler factors. The long-term goal is to build a public mathematical workspace containing code, examples, visualizations, research notes, and data that can support both scholarly work and undergraduate research.

## Overview

Graph theory studies networks of vertices and edges. In the Cops and Robbers game, the graph becomes the playing board. A central question is: how many cops are needed to guarantee capture of the robber?

Some of the questions I am interested in include:

* What is the ordinary cop number of a graph?
* What is the lazy cop number, where at most one cop may move on each cops' turn?
* Once the minimum number of cops is known, what is the optimal capture time?
* How can optimal strategies be represented and visualized?
* What happens on graph products such as Cartesian products and strong products?

## Code Toolkit

I am developing a SageMath toolkit for computing cop number, lazy cop number, capture time, and optimal strategy data for finite graphs.

The toolkit currently includes code for:

* computing ordinary and lazy cop numbers,
* computing capture time,
* saving and loading strategy data,
* exploring optimal robber and cop responses,
* visualizing gameplay on selected graph families.

The code is currently being cleaned up and documented. I plan to make a downloadable version available here soon, with examples and references to the mathematical literature that inspired the implementation.

## Research Notes

This section will eventually collect short notes about active computations, examples, conjectures, and observations from the project. These notes are intended to be more informal than papers, but more durable than social media posts.

Possible topics include:

* visualizing optimal play on torus grids,
* capture-time conventions in computational Cops and Robbers,
* ordinary versus lazy cops on graph products,
* undergraduate research examples,
* how SageMath can be used to explore pursuit-evasion games.

## Visualizations

Because Cops and Robbers is a game, visual examples can be especially helpful. I am developing tools that generate image sequences showing optimal gameplay on particular graphs. These visualizations are experimental, but they may eventually become useful for talks, teaching, and research exploration.

## Open Problems and Current Directions

Current directions include:

* ordinary and lazy Cops and Robbers on Cartesian products of cycles,
* capture time on toroidal grid graphs,
* strategy visualization for graph products,
* computational databases of small graphs and their cop-number data.

## References and Related Work

For general background on pursuit-evasion games on graphs, I recommend Anthony Bonato's book [*An Invitation to Pursuit-Evasion Games and Graph Theory*](https://bookstore.ams.org/view?ProductCode=STML/97). I reviewed that book in the April 2023 issue of *The American Mathematical Monthly*; [the review is available here](https://www.tandfonline.com/doi/full/10.1080/00029890.2023.2172293).

Related links:

* [My Google Scholar profile](https://scholar.google.com/citations?user=KgrsM4cAAAAJ&hl=en)
* [My ResearchGate profile](https://www.researchgate.net/profile/Brendan-Sullivan)
* ["Product Graphs and the Chaser-Runner Game"](https://youtu.be/fWhpjl44ODM), a one-hour talk for the *Talk Math With Your Friends* seminar series
* [The 3x3 rooks graph is the unique smallest graph with lazy cop number 3](https://arxiv.org/abs/1606.08485)
* [An Introduction to Lazy Cops and Robbers on Graphs](https://www.tandfonline.com/doi/abs/10.4169/college.math.j.48.5.322)

## Undergraduate Research

This project is well suited for undergraduate research because it combines concrete examples, computation, visualization, and open-ended mathematical questions. I am especially interested in projects where students can generate examples, test conjectures, build visualizations, or study particular graph families.
