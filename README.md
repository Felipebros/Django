# Django

Exemplo do tutorial do site do Django https://docs.djangoproject.com/pt-br/3.2/intro/tutorial01/

Repositório para testes, leia com mais cuidado antes de colocar em produção, neste link tem mais explicações (https://docs.djangoproject.com/en/3.2/howto/deployment/checklist/) sobre essa SECRET_KEY que está no seguinte link (https://github.com/Felipebros/Django/blob/main/mysite/mysite/settings.py#L23) que deve ser secreta e pode ser utilizada como variável de ambiente.

# Executar
## Setup Linux:

```bash
cd Django
python3 -m venv .venv
source .venv/bin/activate
```
```bash
python -m pip install -r requirements.txt
```
ou
```bash
pip install -r requirements.txt
```

## Executar
```bash
python manage.py runserver
```
ou
```bash
python manage.py runserver 8080
```
