# Python AI Developer — Learning Path

Structured learning project for the **Python Developer (AI)** role, covering the full stack: from classical ML to production deployment.

> Part of the [`ai`](../) repository · Applied learning branch

---

## Context

This project was built to prepare for a **Python AI Developer** role focused on:
- Machine Learning and Deep Learning with PyTorch
- Probabilistic and Bayesian models (HMM, Pyro)
- Transformers and HuggingFace
- Deployment in HPC and production environments

---

## Structure

```
python-ai-developer/
├── 01_ml_fundamentals/
│   └── 01_ml_fundamentals.ipynb
├── 02_deep_learning_pytorch/
│   └── 02_deep_learning_pytorch.ipynb
├── 03_probabilistic_models/
│   └── 03_probabilistic_models.ipynb
├── 04_transformers_huggingface/
│   └── 04_transformers_huggingface.ipynb
├── 05_feature_engineering/
│   └── 05_feature_engineering.ipynb
├── 06_hpc_linux_workflows/
│   └── 06_hpc_linux_workflows.ipynb
├── 07_model_deployment/
│   └── 07_model_deployment.ipynb
└── README.md
```

---

## Roadmap

### Phase 1 — ML Fundamentals `weeks 1–3`

| Topic | Status |
|---|---|
| Learning types: supervised, unsupervised, reinforcement | ⬜ |
| Classic algorithms: regression, trees, SVM, KNN | ⬜ |
| Evaluation: metrics, cross-validation, overfitting | ⬜ |
| End-to-end pipeline with scikit-learn | ⬜ |

→ [`01_ml_fundamentals.ipynb`](01_ml_fundamentals/01_ml_fundamentals.ipynb)

---

### Phase 2 — Deep Learning with PyTorch `weeks 4–7`

| Topic | Status |
|---|---|
| Tensors and autograd | ⬜ |
| Neural networks: layers, activations, backpropagation | ⬜ |
| Training loop: optimizers, loss functions, epochs | ⬜ |
| Basic CNN and RNN | ⬜ |

→ [`02_deep_learning_pytorch.ipynb`](02_deep_learning_pytorch/02_deep_learning_pytorch.ipynb)

---

### Phase 3 — Probabilistic and Bayesian Models `weeks 8–11`

| Topic | Status |
|---|---|
| Probability, distributions, Bayes' Theorem | ⬜ |
| Hidden Markov Models (HMM) | ⬜ |
| Variational inference and MCMC | ⬜ |
| Pyro: probabilistic models on top of PyTorch | ⬜ |

→ [`03_probabilistic_models.ipynb`](03_probabilistic_models/03_probabilistic_models.ipynb)

---

### Phase 4 — Transformers and HuggingFace `weeks 12–14`

| Topic | Status |
|---|---|
| Transformer architecture and attention mechanism | ⬜ |
| HuggingFace pipelines and tokenizers | ⬜ |
| Fine-tuning pretrained models | ⬜ |
| HuggingFace `datasets` and `evaluate` | ⬜ |

→ [`04_transformers_huggingface.ipynb`](04_transformers_huggingface/04_transformers_huggingface.ipynb)

---

### Phase 5 — Feature Engineering and Evaluation `weeks 15–16`

| Topic | Status |
|---|---|
| Data cleaning: null values, outliers | ⬜ |
| Encoding, scaling, transformations | ⬜ |
| Feature selection and importance | ⬜ |
| Advanced metrics: ROC-AUC, F1, Average Precision | ⬜ |

→ [`05_feature_engineering.ipynb`](05_feature_engineering/05_feature_engineering.ipynb)

---

### Phase 6 — HPC and Linux `weeks 17–18`

| Topic | Status |
|---|---|
| Essential Linux commands for Data Science | ⬜ |
| Environment management: conda, venv | ⬜ |
| SLURM: submitting and managing cluster jobs | ⬜ |
| Parallelization: multiprocessing, joblib, CUDA | ⬜ |

→ [`06_hpc_linux_workflows.ipynb`](06_hpc_linux_workflows/06_hpc_linux_workflows.ipynb)

---

### Phase 7 — Production Deployment `weeks 19–20`

| Topic | Status |
|---|---|
| Serialization: pickle, TorchScript | ⬜ |
| REST APIs with FastAPI | ⬜ |
| Docker: containerizing a model | ⬜ |
| MLflow: experiment tracking | ⬜ |

→ [`07_model_deployment.ipynb`](07_model_deployment/07_model_deployment.ipynb)

---

## Stack

```
PyTorch · Pyro · HuggingFace Transformers
scikit-learn · pandas · numpy
FastAPI · Docker · MLflow
SLURM · Linux · CUDA
```

## Setup

```bash
python -m venv venv && source venv/bin/activate
pip install torch transformers datasets evaluate pyro-ppl
pip install scikit-learn pandas numpy matplotlib seaborn
pip install fastapi uvicorn mlflow jupyter
```

## Resources

| Resource | Link |
|---|---|
| Fast.ai — Practical Deep Learning | https://course.fast.ai |
| HuggingFace Course | https://huggingface.co/learn |
| Pyro — Probabilistic Programming | https://pyro.ai |
| Bayesian Methods for Hackers | https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers |