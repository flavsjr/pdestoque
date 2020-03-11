# pdestoque
PD - Controle de Estoque


## Como rodar o projeto?

* Clonar o repositório.
* Crie um virtualenv com Python3
* Ativar o virtualenv.
* Instale as dependências.
* Rode as migrações.

```
git clone https://github.com/flavsjr/pdestoque.git
cd
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```

## Links

[python-decouple](https://github.com/henriquebastos/python-decouple)

[package-of-the-week-python-decouple](https://simpleisbetterthancomplex.com/2015/11/26/package-of-the-week-python-decouple.html)