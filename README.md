create env

```bash
conda create -n wineq python=3.10 -y
```

activate env

```bash
conda activate wineq
```

install requirements

```bash
pip install -r requirements.txt
```

initialize git

```bash
git init
```

initialize dvc

```bash
dvc init
```

track dataset on dvc

```bash
dvc add data_given/wine_quality.csv
```
