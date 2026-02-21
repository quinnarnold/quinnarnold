# Quinn Arnold

Applied Mathematics & Statistics at Bryant University (B.S., December 2026). My interests center on machine learning algorithms, statistical learning, mathematical optimization, and model architecture -- understanding how and why learning systems work, not just applying them.

Pursuing PhD programs and research scientist roles in machine learning.

## Research

**When Spatial Statistics Outperform Machine Learning: Ground-Truth Evaluation of Crime Risk Prediction for Pedestrian Safety Routing**

Comparative evaluation of five risk prediction methods across 1.15M street segments and 18,000 route evaluations per method, demonstrating that temporal-KDE outperforms XGBoost by 42.8% and GNN by 57.4% in crime avoidance for pedestrian routing. The work investigates why simpler statistical methods can outperform complex learned models in structured spatial domains -- a question about model assumptions and inductive bias, not just urban computing.

In submission to *Computers, Environment and Urban Systems* (CEUS). arXiv preprint forthcoming.

## Projects

**[SafeWalk](https://github.com/quinnarnold/safewalk)** -- AI-powered pedestrian safety routing. Risk-weighted Dijkstra routing over city street graphs with a hybrid TypeScript/Python backend on Google Cloud Run and a native SwiftUI iOS app serving Boston, Chicago, and New York. Full pipeline from research to deployed product: OSM graph extraction, KDTree-based crime assignment, XGBoost risk prediction, Pareto-optimal route selection, and Mapbox map-matched navigation.

**[from-scratch](https://github.com/quinnarnold/from-scratch)** -- Neural networks and ML fundamentals built from scratch in Python. Scalar-level automatic differentiation engine with topological-sort backpropagation, multi-layer perceptrons, character-level language models trained on 32K names, and a NumPy-based CNN framework with manual forward/backward passes for all layers (Conv2d, BatchNorm, pooling) targeting CIFAR-10.

## Experience

**SafeWalk** -- Researcher & Developer, September 2025 -- Present. Designed a corridor-based ground-truth evaluation framework comparing five crime risk prediction methods for pedestrian safety routing across three U.S. cities. Built the end-to-end spatiotemporal pipeline and deployed the full system as a hybrid TypeScript/Python backend with a native SwiftUI iOS application.

**Rhode Island Novelty** -- Machine Learning Intern, Summer 2025. Time-series forecasting (90% accuracy), image classification (96--99% accuracy across hierarchical taxonomies), and semantic search using vector embeddings over product and customer data.

## Skills

**Languages:** Python, SQL, Swift, TypeScript, JavaScript, R

**ML and Scientific Computing:** PyTorch, scikit-learn, XGBoost, NumPy, SciPy, pandas, GeoPandas, Shapely, OSMnx

**Algorithms:** Dijkstra, KDTree, graph algorithms (igraph, NetworkX), KDE, UMAP, Pareto optimization

**Tools:** Git, Docker, LaTeX, Google Cloud Platform

## Contact

[LinkedIn](https://www.linkedin.com/in/quinnkarnold) | qarnold@bryant.edu
