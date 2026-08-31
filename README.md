# Get Started

This setup assumes you already have python on your PC.

## Step 1:

install the uv package manager. search it on google:

```
setup uv python
```

After setup verify

```bash
uv --version
```

## Step2:

Pull repo

```bash
git pull https://github.com/NahinM/CSE427-ElectricityConsumptionForecasting.git
```

## Step3:

sync dependencies

```bash
uv sync
```

## Step4:

Download the dataset from [here.](https://www.kaggle.com/datasets/rohitgrewal/electricity-demand-data-dsl?resource=download)

Rename the dataset file as "electricityDemandDataset.csv"
Make sure you place the csv dataset in src/cse427_project

## Step5:

install the VS Code Jupyter Nootbook extension.
connect the extension with the python environment from this project.

Now you're all set.
