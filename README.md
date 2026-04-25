# Lista de Comandos


- Cria o ambiente virtual na pasta venv

```
python -m venv venv 
```

- Instalar todos os pacotes necessários

```python
pip flask 
pip flask-wtf
pip requests
pip pytest
pip pytest-flask
```
ou se houver o arquivo requeriments.txt
```
pip install -r requeriments.txt
```

- Salva a lista de pacotes instalados
- no arquivo requirements.txt
- Isso permite que outras pessoas instalem as mesmas versões
```python
pip frezze > requirements.txt
```

## Criar arquivo .gitignore
- Diz ao git quais arquivos e pastas **Não devem ser versionados**.