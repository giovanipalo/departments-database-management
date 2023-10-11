# Departments Database Management System

O "Departments Database Management System" é um sistema de gerenciamento de banco de dados que permite a criação, manutenção e consulta de informações sobre departamentos de uma organização. Este projeto demonstra como criar um banco de dados, carregar dados de um arquivo CSV e executar consultas usando Python.

## Objetivos

Neste projeto, você aprenderá a:

1. Criar um banco de dados usando Python.

2. Carregar dados de um arquivo CSV para uma tabela no banco de dados.

3. Executar consultas no banco de dados para acessar informações.

## Funcionalidades

- Importação de Dados: O sistema permite a importação de dados de departamentos de um arquivo CSV.

- Banco de Dados: Os dados importados são armazenados em um banco de dados SQLite para facilitar a recuperação e manipulação.

- Consultas: O sistema oferece suporte a várias consultas, incluindo a exibição de todos os registros, a exibição apenas do nome do departamento e a contagem total de registros.

## Estrutura do Repositório

O repositório contém os seguintes arquivos:

- `.gitattributes`: Arquivo de configuração do Git.
- `Departments.db`: Banco de dados SQLite onde os dados são armazenados.
- `README.md`: Este arquivo de documentação.
- `database_manager.py`: Código Python que implementa a criação do banco de dados, importação dos dados do arquivo CSV e execução de consultas.
- `Departments.csv`: Arquivo CSV que contém os dados a serem importados.

## Pré-requisitos e Instalação

Certifique-se de que você tenha a seguinte biblioteca Python instalada:

- `pandas`: Para manipulação de dados tabulares.

Você pode instalar essas bibliotecas usando o pip:

`pip install pandas`

## Execução do Projeto

Para executar o projeto, siga os passos abaixo:

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter a biblioteca `pandas` instalada.
3. Execute o arquivo `database_manager.py`.

Isso iniciará o processo de importação de dados do arquivo CSV para um banco de dados SQLite, criando um DataFrame e armazenando os dados no banco de dados.
