# Quinn Arnold

Applied Mathematics & Statistics at Bryant University (B.S., December 2026). My work centers on machine learning, reinforcement learning, optimization, and safety-focused applied ML systems: building models, testing where they fail, and connecting learned signals to downstream decisions under constraints.

I am especially interested in reinforcement learning, game theory, LLM safety, decision-focused learning, graph algorithms, and responsible ML evaluation. Current work spans deep RL for combinatorial auctions, prompt-injection defense for LLM systems, KDE-residual GNN architectures, and ML model governance focused on bias assessment and production-readiness review.

## Research & Technical Experience

**Advanced Analytics Intern, MAPFRE Insurance**

Contributing to machine-learning model governance work focused on bias assessment, mitigation, and production-readiness review across Python, statistical analysis, multivariate methods, AWS SageMaker, and enterprise development workflows. Also developing LLM-assisted image-analysis workflows that compare visual hazard descriptions against inspection reports to surface discrepancies for underwriting review.

**Founder & Researcher, GuidePost Technologies LLC**

Co-authored a police-informed patrol-routing research paper currently under peer review, studying crime-weighted loop generation and coverage tradeoffs on a 24,000-node street network. Developed KDE-weighted graph-routing and fleet-coordination algorithms, parity-tested core behavior across 5,000+ simulated patrol shifts with 800+ tests passing, and built the production decision-support platform for route generation, officer workflow support, dispatch interruption handling, authentication, WebSocket recovery, and audit exports.

**Machine Learning Intern, Rhode Island Novelty**

Built time-series forecasting models with automated feature engineering and scenario simulation for inventory and revenue planning. Built an image-classification pipeline achieving 96-99% accuracy across hierarchical product taxonomies with automated metadata extraction and label inconsistency detection. Engineered a semantic-search system using vector embeddings to translate natural-language business queries into executable SQL over product and customer data.

**Researcher & Developer, SafeWalk**

Built pedestrian-safety routing and evaluation systems comparing classical spatial methods and learned models across 36,000 routes on Chicago's 1.15M-segment walking network, motivating later decision-focused learning work. Developed spatiotemporal risk pipelines with graph extraction, crime-to-edge assignment, rolling-window features, and route-level evaluation for downstream routing objectives.

## Selected Work

**Reinforcement Learning for Combinatorial Auctions**

Investigating failure modes and generalization gaps in a deep-RL combinatorial-auction system after strong CAT scheduling results but poor transfer to broader auction settings; current Bryant faculty/student research collaboration.

**[Ask Tupper / LLM Injection Defense](https://github.com/quinnarnold/llm-injection-defense)**

Fine-tuned Qwen3-32B with QLoRA on a single consumer GPU in 90 minutes; built a six-layer prompt-injection defense pipeline reducing attack success from 20% to 0% across 15 vectors. Custom RoBERTa classifier achieves 95.3% injection recall; hybrid RAG over 530 university documents lifts factual accuracy from 60% to 74%.

**KDE-Residual GNN with Decision-Focused Learning**

Built a frozen KDE structural prior plus learned GNN residual architecture trained through differentiable optimization to improve downstream constrained-routing decisions rather than pointwise prediction accuracy.

**[Neural Networks from Scratch](https://github.com/quinnarnold/from-scratch)**

Implemented neural-network and machine-learning fundamentals from first principles, including scalar-level automatic differentiation, backpropagation, multilayer perceptrons, and character-level language models.

## Skills

**Languages:** Python, SQL, Swift, TypeScript, JavaScript, R

**ML & Deep Learning:** PyTorch, PyTorch Geometric, QLoRA, RoBERTa, RAG, reinforcement learning, model evaluation, bias assessment, automatic differentiation, backpropagation, gradient descent

**Algorithms & Mathematics:** optimization, statistical learning, multivariate analysis, graph algorithms, Dijkstra, KDTree, KDE, UMAP, Pareto optimization

**Scientific Computing & Tools:** NumPy, SciPy, pandas, GeoPandas, Shapely, OSMnx, H3, Matplotlib, Git, Docker, AWS SageMaker

## Links

[Portfolio](https://quinnarnold.github.io/portfolio/) | [LinkedIn](https://www.linkedin.com/in/quinnkarnold) | [GitHub](https://github.com/quinnarnold) | qarnold@bryant.edu
