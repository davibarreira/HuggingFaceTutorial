# HuggingFaceTutorial

Tutorials on how to use Transformers for NLP.

## Setup Notebook

To setup the notebook do the following. Inside the
`/notebooks` directory, run
```
conda env create -f environment.yml
```
This will create an environment `book`. Next, do
```
conda activate book
```
to enter the environment, and install the ipykernel
```
conda install ipykernel
ipython kernel install --user --name=huggingface
```

Now you can deactivate the environment and run
```
jupyter-lab
```
to enter JupyterLab, with the `huggingface` kernel available
with all the packages installed.
