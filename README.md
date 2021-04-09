# namespace package packaging problem

pdm init
pdm add ./bar
pdm add ./namespace

pdm run python main.py
