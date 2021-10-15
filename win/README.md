## 環境の構築
基本的にwindowsでもubuntuでも仮想環境を構築する必要があります。
```
set VENV=py39
python -m venv C:\Users\yohei\python_env\%VENV%
```
## ライブラリのインストール
```
set VENV=py39
CALL C:\Users\yohei\python_env\%VENV%\Scripts\activate.bat
python -m pip install -U pip

python -m pip install Flask
```
## 内容
- [quickstart](../win/quickstart/README.md)
- [tutorial](../win/tutorial/README.md)
