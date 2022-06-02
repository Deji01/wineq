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

add all changes made to the staging area

```bash
git add .
```

commit changes with message

```bash
git commit -m "first commit"
```

chaining command

```bash
git add . && git commit -m "update README.md"
```

add github repository

```bash
git remote add origin https://github.com/Deji01/wineq.git
```

rename current branch name

```bash
git branch -M main
```

push changes

```bash
git push origin main
```
