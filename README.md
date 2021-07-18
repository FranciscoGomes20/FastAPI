# FastAPI
Uma API de teste feito utilizando FastAPI para fins de estudo.

## Instalação
Inicie um ambiente virtual, nesse projeto usarei virtualenv.

```
python -m venv venv
```

Logo depois acesse a pasta do ambiente virtual pelo terminal ativado pelo arquivo activate.

````
venv\Scripts\activate
````
## Dependências do projeto
Usando o gerenciador de pacotes do python para baixar todas as bibliotecas utilizadas pela Api encontradas no arquivo requirements.txt.

````
pip install -r requirements.txt
````

## Executando o projeto localmente
Agora devera ser iniciado o servidor local, usaremos o uvicorn para isso.

````
uvicorn main:app --reload
````
Se não houver nenhum erro, a Api estará rodando e ira mostrar uma URL no servido em sua máquina local.

A partir dai você poderar utilizar a Api e fazer testes.
