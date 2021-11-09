# Common Python Data Structures (Guide)

Esse repositório contém os exercícios e anotações do tutorial
[Common Python Data Structures (Guide)](https://realpython.com/python-data-structures/), do site [Real Python](https://realpython.com/).

## Ferramentas usadas nesse repositótio

### Autopep8

Autopep8 é uma ferramenta para formatar o código Python de acordo com as
regras de formatação do PEP8.

### MyPy

Mypy é um verificador de tipo estático opcional para o Python, que visa
combinar os benefícios da tipagem dinâmica (ou "duck typing") e da
tipagem estática. Para mais informações, veja
[http://mypy-lang.org/](https://mypy-lang.org/).

Para usar o MyPy, basta instalar o pacote
[mypy-lang](https://pypi.org/project/mypy-lang/) e executar o comando
`mypy .` na pasta do repositório.

```shell
> mypy .
Success: no issues found in 7 source files
```

### Flake8

O Flake8 é um verificador de código Python que verifica padrões de
estilo. Para mais informações, veja
[http://flake8.pycqa.org/](https://flake8.pycqa.org/).

Para usar o flake8, basta instalar o pacote
[flake8](https://pypi.org/project/flake8/) e executar o comando
`flake8` na pasta do repositório.

```shell
flake8 .
```

### Pre-commit

O pre-commit é um gerenciador de pacotes multilíngue para pre-commits
hooks. É através dele que o flake8 é executado. Para mais informações,
veja [https://pre-commit.com/](https://pre-commit.com/)

Pra usar o pre-commit, é preciso primeiro instalar os pré-commits no
git, com o comando

```shell
> pre-commit install
pre-commit installed at .git\hooks\pre-commit
```

Pra testar o pre-commit, use o comando

```shell
> pre-commit run --all-files
flake8..........................................................Passed
```

Se for preciso atualizar o pre-commit, use o comando

```shell
 pre-commit autoupdate
```