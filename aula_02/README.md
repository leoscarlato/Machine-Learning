# Preparing the workspace

- Install Anaconda (https://www.anaconda.com/download) for your operating system. When asked if you want to run `conda init`, say yes.

- Open a conda-enabled terminal. In Windows you have to open the "Anaconda prompt". In Linux/MacOS open a regular terminal, you should see the text "`(base)`" in the beginning of the prompt, indicating that the conda environment variables are active for this terminal.

- Run the command below to create a conda environment:

```bash
conda env create -f environment.yml
```

# Working in your environment

- Change into your newly created environment:

```bash
conda activate ml
```

# Support material for exploratory data analysis (EDA)

https://github.com/FabioAyresInsper/ames
