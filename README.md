# MLSA-project

In this project, we have developed a machine learning-based code autocompletion tool for Python code snippets using PyTorch. The model will suggest the next token of a snippet of code. We have used the Py150 dataset as code source for the training phase and we have fine-tuned the codeBERT model.

# Project structure

The project is composed by 3 notebooks:
- <b>Project:</b> Contains the whole project: Data preparation, model training, model evaluation, inference;
- <b>Training:</b> Contains only the training phase: Data preparation, model training and evaluation;
- <b>Inference:</b> Contains the code for inference purposes. It will load the saved model that we have trained and does some code completion of some snippets.
