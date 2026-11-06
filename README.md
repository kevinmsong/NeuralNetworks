# NeuralNetworks

Notebooks that implement neural-network building blocks and small training experiments from scratch or with Keras/PyTorch.

## Projects

| Notebook | Summary |
|----------|---------|
| `AdaGradOptimizer.ipynb` | Custom AdaGrad gradient-descent optimizer implemented from scratch |
| `LogisticRegression.ipynb` | Neural-network-style logistic regression trained from scratch in PyTorch |
| `MNIST.ipynb` | Feedforward nets in Keras for handwritten MNIST digits (reported best macro average test F1 ~97%) |
| `TranscriptionFactorBinding.ipynb` | Neural net to predict presence/absence of transcription-factor binding sites in DNA fragments |

## Setup

```bash
pip install jupyter numpy tensorflow keras torch
jupyter notebook
```

Open the notebook you want to run. Some notebooks may expect local datasets (e.g. MNIST via Keras loaders, or course-provided DNA sequences).

## Related

Classical (non-neural) ML notebooks live in [MachineLearning](https://github.com/kevinmsong/MachineLearning).
