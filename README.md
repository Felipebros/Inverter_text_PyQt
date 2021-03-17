# text_inverter_PyQt
Inverte texto feito em python com visual em [Qt](https://www.qt.io/)

![Imagem do programinha](https://github.com/Felipebros/Inverter_text_PyQt/blob/main/Captura%20de%20tela_2020-06-24_11-17-39.png)

# Converter .ui para .py
```bash
pyuic5 input.ui -o output.py
```

# Executar
Setup:

```
cd myproject
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

ou Setup:
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
