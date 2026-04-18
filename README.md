# PYTORCH-DEEP-LEARNING
Progressive deep learning projects on FashionMNIST  - ANN, CNN, Transfer learning with optuna tuning and MLflow/DagsHub tracking


# PyTorch Vision Experiments

Deep learning projects built with PyTorch on the Fashion MNIST dataset, 
progressing from ANN to CNN to Transfer Learning.

## Projects
- **ANN** — Fully connected network with Optuna hyperparameter search and MLflow experiment tracking
- **CNN** — Convolutional network (coming soon)
- **Transfer Learning** — Fine-tuning pretrained model (coming soon)

## Tech Stack
PyTorch · Optuna · MLflow · DagsHub · Python

## Experiment Tracking
Live MLflow runs on DagsHub:
[View Experiments]([https://dagshub.com/Ashi743/your-repo-name](https://dagshub.com/deendayalbhai420/custom_mlflow_repo.mlflow/#/experiments/0/runs?searchFilter=&orderByKey=attributes.start_time&orderByAsc=false&startTime=ALL&lifecycleFilter=Active&modelVersionFilter=All+Runs&datasetsFilter=W10%3D))

## Results (ANN)
| Metric | Value |
|--------|-------|
| Best Val Accuracy | 89% |
| Best LR | 0.018 |
| Best Batch Size | 32 |
| Best Dropout Rate | 0.355 |
| Best Neurons per layers | 88 |
| Best optimizer | SGD |

## Setup
pip install -r requirements.txt
