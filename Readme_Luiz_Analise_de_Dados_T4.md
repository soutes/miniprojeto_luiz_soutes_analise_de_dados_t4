## Instruções para Execução

1. Clone o repositório
2. Certifique-se de que o arquivo `data/base_varejo.csv` está na pasta correta
3. Abra o arquivo `analise_varejo.ipynb` no VS Code ou Google Colab
4. Execute todas as células em ordem (Shift + Enter)

## Dependências

O projeto utiliza **Poetry** para gerenciamento de dependências.

### Instalar o Poetry (caso não tenha):

pip install poetry

## Instale as dependências:
poetry install

## Ativar o ambiente virtual
poetry shell

## Como rodar

### VS Code:
Instale a extensão Python

Certifique-se de que o kernel está usando o ambiente virtual do Poetry

Abra o arquivo .ipynb

Clique em "Run All"

### Google Colab:
Faça upload do arquivo .ipynb

Execute: Runtime > Run all

## Estrutura

miniprojeto_python/

├── analise_varejo.ipynb   # Notebook principal

├── data/

    └── base_varejo.csv    # Base de dados

├── pyproject.toml         # Configuração do Poetry

├── poetry.lock            # Lock das dependências

├── README.md              # Descrição do projeto

└── Readme_Luiz_Analise_de_Dados_T4.md     # Este arquivo
