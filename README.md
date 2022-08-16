# Sample Project

## Set environment

```
conda create --prefix ./env jupyter pandas numpy matplotlib scikit-learn
```

## Check active environment

```
conda env list
```

## Select an environment

```
conda activate <path/to/environment>
```

## Open Jupyter Notebook

```
jupyter notebook
```

## Deactivate

```
conda deactivate
```

## Share project

```
conda env export --prefix <path/to/env> > environment.yml
```

## Create an environment from yml

```
conda env create --file environment.yml  --name env
```

### References

- [Create environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)
- [Conda docs](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#sharing-an-environment)
