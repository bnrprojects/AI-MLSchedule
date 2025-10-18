# AI-ML Learning Schedule

This plan structures the next several weeks of study around four parallel workstreams: core mathematics review, probability and statistics practice, scientific Python proficiency, and development environment setup. Each week lists the learning materials, tangible outputs, and checkpoints to track progress.

## Week 1: Linear Algebra Foundations & Environment Setup

- **Linear Algebra**
  - Watch Gilbert Strang’s MIT OCW *Linear Algebra* Lecture 1–2.
  - Take notes on vector spaces, linear independence, and matrix multiplication.
  - Complete problem set covering basic vector operations and solving small linear systems.
- **Probability & Statistics**
  - Read *Think Stats* Chapter 1 (Exploratory Data Analysis).
  - Implement notebook exercises computing frequency tables and simple probability estimates.
- **Scientific Python**
  - Install Miniconda/pyenv and create a dedicated `ml-learning` environment.
  - Work through NumPy quickstart (array creation, slicing, broadcasting).
  - Write a script that converts a small Java array-processing example into NumPy code.
- **Dev Environment**
  - Configure VS Code with Python extensions and Jupyter support.
  - Initialize Git in your workspace and set up a pre-commit hook for formatting (e.g., `black`).

## Week 2: Matrix Operations & Probability Distributions

- **Linear Algebra**
  - Watch Lectures 3–4 focusing on matrix factorizations and inverses.
  - Solve problem set on matrix algebra and determinants.
- **Probability & Statistics**
  - Review Khan Academy modules on discrete and continuous distributions.
  - Build a notebook exploring Bernoulli, Binomial, Normal, and Poisson distributions via plots and simulations.
- **Scientific Python**
  - Learn pandas DataFrame basics: loading CSVs, selecting columns, filtering rows.
  - Recreate Java-style data parsing logic using pandas idioms.
- **Dev Environment**
  - Document environment setup steps and daily workflow in a `docs/workflow.md` journal.
  - Experiment with Docker by containerizing the notebook environment.

## Week 3: Eigenvalues & Bayesian Reasoning

- **Linear Algebra**
  - Watch Lectures 5–6 on eigenvalues and eigenvectors.
  - Complete problem set deriving eigenvalues for 2×2 and 3×3 matrices and interpreting eigenspaces.
- **Probability & Statistics**
  - Study Bayes’ theorem applications (Khan Academy or *Think Stats* Chapters 2–3).
  - Implement Bayesian updating examples in a notebook (medical testing, spam filtering).
- **Scientific Python**
  - Practice matplotlib for data visualization: histograms, scatter plots, line charts with annotations.
  - Build a mini-report notebook combining pandas analysis with matplotlib visuals.
- **Dev Environment**
  - Configure linting/formatting automation (e.g., `ruff`, `black`, `isort`).
  - Set up Git hooks to enforce notebook clearing or linting before commits.

## Week 4: Consolidation & Project Prep

- **Linear Algebra**
  - Review Lectures 1–6 summaries and attempt a comprehensive problem set blending concepts.
  - Explore applications to machine learning (e.g., PCA overview).
- **Probability & Statistics**
  - Conduct a hypothesis testing case study using synthetic or public data.
  - Document interpretations and statistical assumptions in the notebook.
- **Scientific Python**
  - Integrate NumPy, pandas, and matplotlib in a small end-to-end data pipeline script.
  - Refactor code to emphasize Pythonic patterns compared to Java equivalents.
- **Dev Environment**
  - Finalize documentation of tooling, shortcuts, and workflow habits in `docs/workflow.md`.
  - Review Docker setup; create a reusable `Dockerfile` or compose snippet for future ML projects.

## Tracking & Accountability

- Maintain a checklist for each week’s tasks and mark completion dates.
- Use Git commits to version control notebooks, scripts, and documentation.
- Schedule weekly retrospectives to identify challenges, adjust pacing, and plan next steps.
