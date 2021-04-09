Conectcar-bot
---

Crie um ambiente para execução do RASA:
```sh
python3 -m venv venv
```

Carregue seu ambiente:
```sh
source /venv/bin/activate
```

Instale os requisitos:
```sh
pip install -r requirements.txt
```

Treine o modelo:
```sh
rasa train
```

Teste o modelo:
```sh
rasa shell
```
