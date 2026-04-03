# Quinn Arnold

Applied Mathematics & Statistics at Bryant University (B.S., December 2026). My interests center on machine learning algorithms, deep learning architectures, mathematical optimization, and how model and architecture choices shape downstream performance in real-world systems — understanding how and why learning systems work, not just applying them. Broader interests include computer vision, agentic AI, graph algorithms, distributed training, safety & alignment, and spatial statistics.

Pursuing PhD programs and research scientist roles in machine learning.

## Research

**When Spatial Statistics Outperform Machine Learning: Corridor-Based Ground-Truth Evaluation of Crime Risk Prediction for Pedestrian Safety Routing**

Comparative evaluation of five risk prediction methods across 1.15M street segments and 36,000 route evaluations per method, demonstrating that KDE achieves 54.5% greater crime avoidance than XGBoost and 53.3% greater than GNN for pedestrian routing. The work investigates why simpler statistical methods can outperform complex learned models in structured spatial domains — a question about model assumptions and inductive bias, not just urban computing.

Submitted to *Journal of Transport Geography* (Elsevier). 2026.

**Adaptive Patrol Route Optimization** *(in progress)*

Dynamic patrol routing system generating shift-aware routes optimized for crime deterrence using continuously updated spatial risk surfaces. Evaluates multiple routing strategies against real holdout crime data across a major U.S. city, with a fleet coordination layer for multi-officer dispatch and mid-patrol reallocation. Targeting journal submission and department pilot, Summer 2026.

**Decision-Focused Spatial Prediction Architecture** *(in progress)*

Novel architecture bridging the gap between prediction accuracy and downstream decision quality for spatial optimization tasks. Explores decision-focused learning where the model optimizes directly for routing outcomes rather than crime count prediction — addressing the predict-then-optimize misalignment identified in the SafeWalk paper. Targeting NeurIPS 2026 Workshop.

## Projects

**[SafeWalk](https://apps.apple.com/us/app/safewalk-ai/id6754341043)** — AI-powered pedestrian safety routing. Risk-weighted Dijkstra routing over city street graphs with a hybrid TypeScript/Python backend on Oracle OCI and a native SwiftUI iOS app serving three U.S. cities. Full pipeline from research to deployed product: OSM graph extraction, KDTree-based crime assignment, KDE risk surfaces, Pareto-optimal route selection, and Mapbox map-matched navigation.

**[from-scratch](https://github.com/quinnarnold/from-scratch)** — Neural networks and ML fundamentals built from scratch in Python. Scalar-level automatic differentiation engine with topological-sort backpropagation, multi-layer perceptrons, character-level language models trained on 32K names, and a NumPy-based CNN framework with manual forward/backward passes for all layers (Conv2d, BatchNorm, pooling) targeting CIFAR-10.

## Experience

**SafeWalk** — Researcher & Developer, September 2025 — Present. Designed a corridor-based ground-truth evaluation framework comparing five crime risk prediction methods for pedestrian safety routing across three U.S. cities. Built the end-to-end spatiotemporal pipeline and deployed the full system as a hybrid TypeScript/Python backend on Oracle OCI with a native SwiftUI iOS application.

**Rhode Island Novelty** — Machine Learning Intern, Summer 2025. Time-series forecasting (90% accuracy), image classification (96–99% accuracy across hierarchical taxonomies), and semantic search using vector embeddings over product and customer data.

**MAPFRE Insurance** — Advanced Analytics Intern, Summer 2026 (Incoming). Predictive models and ML applications for insurance risk assessment.

## Skills

**Languages:** Python, SQL, Swift, TypeScript, JavaScript, R

**ML and Scientific Computing:** PyTorch, scikit-learn, XGBoost, NumPy, SciPy, pandas, GeoPandas, Shapely, OSMnx

**Algorithms:** Dijkstra, KDTree, graph algorithms (igraph, NetworkX), KDE, UMAP, Pareto optimization

**Tools:** Git, Docker, LaTeX, Oracle OCI

## Contact

[Portfolio](https://quinnarnold.github.io/portfolio/) | [LinkedIn](https://www.linkedin.com/in/quinnkarnold) | qarnold@bryant.edu
