# Jornada de Trabalho

Este notebook (`analise-horas.ipynb`) contém um exercício prático para exemplificar uma tarefa de um cientista de dados.

Contextualizando: em uma determinada empresa, o sistema de registro de ponto utilizado permite a exportação de registros em um intervalo de tempo para o e-mail do usuário. A partir dessa informação, é possível extrair dados relevantes sobre a jornada de trabalho e carga horária de um indivíduo. O processo de análise está organizado para seguir o conceito de ETL.

O desenvolvimento deste trabalho se deu em virtude da VII SAET, realizada na UTFPR - Câmpus Toledo, entre os dias 23 e 26 de outubro de 2023.

A apresentação pode ser visualizada aqui: https://pt.slideshare.net/LucasCosta261/dia-a-dia-do-cientista-de-dados-saet-2023pptx

## Rodando localmente

Para rodar o notebook localmente, é recomendado usar um ambiente virtual Python. A versão usada é a 3.10.13.

```bash
$ conda create -n <nome_ambiente> python=3.10.13
$ # ou
$ virtualenv --python="/usr/bin/python3.10.13" "/path/to/new/virtualenv/"
```

> A configuração e instalação de ambientes virtuais e versões diferentes de Python fogem do escopo deste exercício.

Depois, basta instalar os requisitos usando `pip`, por exemplo:

```bash
$ pip install -r requirements.txt
```

Para abrir o notebook, use sua IDE preferida, como VS Code por exemplo, que tem extensões próprias para manipulação de Jupyters Notebooks.
