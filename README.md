# Environment

## Create virtual environment

```cmd
python -m venv ve
```

## Activate virtual environment

```cmd
.\ve\Scripts\activate
```

## Install requirements

```bash
python -m pip install --upgrade pip
pip install PyQt5
pip install lxml
pyrcc5 -o libs/resources.py resources.qrc
```

```bash
git add . & git commit -am "test 1"
git push
```