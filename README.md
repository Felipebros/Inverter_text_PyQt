# text_inverter_PyQt
Inverte texto feito em python com visual em [Qt](https://www.qt.io/)

![Imagem do programinha](https://github.com/Felipebros/Inverter_text_PyQt/blob/main/Captura%20de%20tela_2020-06-24_11-17-39.png)


## Índice

* [Converter .ui para .py](#converter-ui-para-py)
* [Executar](#executar)
* [Setup Linux](#setup-linux)
* [Setup Windows](#setup-windows)
* [ou Setup virtualenv](#ou-setup-virtualenv)
* [Compile](#compile)


# Converter .ui para .py
```bash
pyuic5 input.ui -o output.py
```

# Executar
## Setup Linux:

```
cd myproject
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```


## Setup Windows:

```
cd myproject
python -m venv .venv
source .venv/Scripts/activate
pip install -r requirements.txt
```

## ou Setup virtualenv:
```bash
sudo pip install virtualenv
```
```bash
virtualenv --python='/usr/bin/python3' env
```
```bash
source env/bin/activate
```
```bash
pip install -r requirements.txt
```
```bash
python mainwindow.py
```

# Compile:

```
pyinstaller --name="Read-File" --onefile read_file.py
```
