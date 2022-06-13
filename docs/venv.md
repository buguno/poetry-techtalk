# Ambientes virtuais

Com o módulo [venv](https://docs.python.org/pt-br/3/library/venv.html) é possível criar "ambientes virtuais" onde são instalados pacotes de versões distintas dos usados globalmente no sistema.

## Criando um ambiente virtual e ativando

Para criar um ambiente virtual é preciso rodar o comando abaixo e logo depois é preciso ativar usando o comando source.

```bash
python3 -m venv venv
source venv/bin/activate
```

## Pip

O pip é um sistema que gerencia pacotes na linguagem Python.

Ou seja, ele faz buscas de pacotes na fonte padrão para pacotes e suas dependências – Python Package Index ([PyPI](https://pypi.org/)).

Para instalar pacotes usamos o comando abaixo.

```bash
pip install nome-do-pacote
```

Ou caso seu projeto use um arquivo de requirements, basta usar o comando abaixo.

```bash
pip install requirements.txt
```
