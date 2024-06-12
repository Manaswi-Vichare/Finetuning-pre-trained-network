# Finetuning-pre-trained-network
Finetuning the pre-trained ResNet101 model on the STL10 dataset for classification tasks. Analyzing the performance using three different optimizers: Adam, Adagad, and Adadelta.

**Language used:** Python

**Libraries used:** torch, torchvision, matplotlib, sklearn

**Dataset:** STL10 dataset

**Dataset Visualization:**

<img src=https://github.com/Manaswi-Vichare/Finetuning-pre-trained-network/assets/83514527/ec3fda24-bbbc-48fe-a704-3a95ef7e8795, width=400>

**Observations:**

| Epochs | Optimizer | Train Loss | Train Accuracy | Test Accuracy |
| -- | -- | -- | -- | -- |
| 10 | Adam | 0.1250 | 95.68% | 80.78% |
| 10 | Adagrad | 0.0772 | 97.80% | 73.24% |
| 10 | Adadelta | 0.0416 | 98.50% | 86.09% |
