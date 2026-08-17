# Análise Exploratória de Dados - Varejo

Este projeto faz parte do **1º Miniprojeto - Analista de Dados - Turma 4**.

O objetivo é realizar uma análise exploratória em uma base de dados de vendas do varejo, aplicando conceitos básicos de tratamento e visualização de dados com Python.

## 📊 O que foi feito

- Importação e limpeza dos dados
- Conversão de tipos (datas e IDs)
- Análise de vendas ao longo do tempo
- Análise do perfil dos clientes (número de filhos)

## 🛠️ Tecnologias

- Python
- Pandas
- Matplotlib
- Seaborn

## 📁 Dataset

Base Varejo (https://www.kaggle.com/datasets/namespaiva/base-varejo)
Dicionário de dados:
1. DATA: Data da compra;
2. CO_ID: Identificação do número de compra (número da nota fiscal);
3. CL_ID: Identificação do cliente (número do cliente);
4. CL_GENERO: Sexo biológico informado pelo cliente;
5. CL_EC: Estado civil do cliente, sendo:
    1: Casado ou união estával;
    2: Divorciado;
    3: Separado;
    4: Solteiro;
    5: Viúvo.
6. CL_FHL: Número de filhos do cliente;
7. CL_SEG: Segmentação econômica do cliente (classe A, B ou C);
8. PR_ID: Código do produto (SKU) adquirido;
9. PR_CAT: Categoria do produto adquirido;
10. PR_NOME: Nome do produto adquirido.

RangeIndex: 830000 entries, 0 to 829999
Data columns (total 14 columns):
 #   Column       Non-Null Count   Dtype  
---  ------       --------------   -----  
 0   DATA         830000 non-null  str    
 1   CO_ID        830000 non-null  int64  
 2   CL_ID        830000 non-null  int64  
 3   CL_GENERO    830000 non-null  str    
 4   CL_EC        830000 non-null  int64  
 5   CL_FHL       830000 non-null  int64  
 6   CL_SEG       830000 non-null  str    
 7   PR_ID        830000 non-null  int64  
 8   PR_CAT       830000 non-null  str    
 9   PR_NOME      830000 non-null  str    
 10  Unnamed: 10  0 non-null       float64
 11  Unnamed: 11  0 non-null       float64
 12  Unnamed: 12  0 non-null       float64
 13  Unnamed: 13  0 non-null       float64
dtypes: float64(4), int64(5), str(5

Base com **830.000 registros** de vendas, contendo informações sobre clientes, produtos e datas das compras.