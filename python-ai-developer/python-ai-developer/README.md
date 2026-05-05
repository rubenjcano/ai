# Python AI Developer — Learning Path

Proyecto de aprendizaje estructurado para el rol de **Python Developer (IA)**, cubriendo el stack completo del puesto: desde ML clásico hasta despliegue en producción.

> Parte del repositorio [`ai`](../) · Rama de aprendizaje aplicado

---

## Contexto

Este proyecto nació para preparar el rol de **Desarrollador Python (IA)** con foco en:
- Machine Learning y Deep Learning con PyTorch
- Modelos probabilísticos y bayesianos (HMM, Pyro)
- Transformers y HuggingFace
- Despliegue en entornos HPC y producción

---

## Estructura

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

### Fase 1 — Fundamentos de ML `semanas 1–3`

| Tema | Estado |
|---|---|
| Tipos de aprendizaje: supervisado, no supervisado, refuerzo | ⬜ |
| Algoritmos clásicos: regresión, árboles, SVM, KNN | ⬜ |
| Evaluación: métricas, cross-validation, overfitting | ⬜ |
| Pipeline end-to-end con scikit-learn | ⬜ |

→ [`01_ml_fundamentals.ipynb`](01_ml_fundamentals/01_ml_fundamentals.ipynb)

---

### Fase 2 — Deep Learning con PyTorch `semanas 4–7`

| Tema | Estado |
|---|---|
| Tensores y autograd | ⬜ |
| Redes neuronales: capas, activaciones, backpropagation | ⬜ |
| Loop de entrenamiento: optimizadores, loss, epochs | ⬜ |
| CNN y RNN básicas | ⬜ |

→ [`02_deep_learning_pytorch.ipynb`](02_deep_learning_pytorch/02_deep_learning_pytorch.ipynb)

---

### Fase 3 — Modelos Probabilísticos y Bayesianos `semanas 8–11`

| Tema | Estado |
|---|---|
| Probabilidad, distribuciones, Teorema de Bayes | ⬜ |
| Hidden Markov Models (HMM) | ⬜ |
| Inferencia variacional y MCMC | ⬜ |
| Pyro: modelos probabilísticos sobre PyTorch | ⬜ |

→ [`03_probabilistic_models.ipynb`](03_probabilistic_models/03_probabilistic_models.ipynb)

---

### Fase 4 — Transformers y HuggingFace `semanas 12–14`

| Tema | Estado |
|---|---|
| Arquitectura Transformer y mecanismo de atención | ⬜ |
| Pipelines y tokenizers de HuggingFace | ⬜ |
| Fine-tuning de modelos preentrenados | ⬜ |
| `datasets` y `evaluate` de HuggingFace | ⬜ |

→ [`04_transformers_huggingface.ipynb`](04_transformers_huggingface/04_transformers_huggingface.ipynb)

---

### Fase 5 — Feature Engineering y Evaluación `semanas 15–16`

| Tema | Estado |
|---|---|
| Limpieza de datos: nulos, outliers | ⬜ |
| Encoding, escalado, transformaciones | ⬜ |
| Selección de features e importancia | ⬜ |
| Métricas avanzadas: ROC-AUC, F1, Average Precision | ⬜ |

→ [`05_feature_engineering.ipynb`](05_feature_engineering/05_feature_engineering.ipynb)

---

### Fase 6 — HPC y Linux `semanas 17–18`

| Tema | Estado |
|---|---|
| Comandos Linux esenciales para Data Science | ⬜ |
| Gestión de entornos: conda, venv | ⬜ |
| SLURM: lanzar y gestionar jobs en clústeres | ⬜ |
| Paralelización: multiprocessing, joblib, CUDA | ⬜ |

→ [`06_hpc_linux_workflows.ipynb`](06_hpc_linux_workflows/06_hpc_linux_workflows.ipynb)

---

### Fase 7 — Despliegue en Producción `semanas 19–20`

| Tema | Estado |
|---|---|
| Serialización: pickle, TorchScript | ⬜ |
| APIs con FastAPI | ⬜ |
| Docker: contenerizar un modelo | ⬜ |
| MLflow: tracking de experimentos | ⬜ |

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

## Recursos

| Recurso | Enlace |
|---|---|
| Fast.ai — Practical Deep Learning | https://course.fast.ai |
| HuggingFace Course | https://huggingface.co/learn |
| Pyro — Probabilistic Programming | https://pyro.ai |
| Bayesian Methods for Hackers | https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers |
