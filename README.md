# 📊 Challenge Telecom_X: Análise de Evasão de Clientes em Telecomuinicação
Este repositório contém a solução desenvolvida para o desafio da formação One Tech Foundation - Especialização em Data Science, 
uma parceria entre Alura e Oracle Next Education (ONE).

## 🔍 Objetivo
A Telecom_X, empresa do setor de telecomunicações, enfrenta altos índices de cancelamento (churn). Este projeto visa:
- Coletar os Dados Fornecidos
- Explorar os Dados
- Transformar os Dados
- Gerar Visualizações
- Analisar os Dados
- Gerar Insights

## 🛠️ Tecnologias Utilizadas
 [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
 [![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
 [![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)

 [![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)](https://matplotlib.org/)
 [![Seaborn](https://img.shields.io/badge/Seaborn-8B1A1A?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org/)
 [![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)](https://jupyter.org/)

## 📂 Conjunto de Dados
A Telecom_X forneceu os dados no formato `JSON`, contendo inicialmente **7.267 registros de clientes**, cada um com **21 atributos** distintos. 
Essas informações representam o perfil dos usuários, incluindo dados contratuais, serviços contratados e comportamentais.

```json
{
  "fonte": "Telecom_X",
  "url": "https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/refs/heads/main/TelecomX_Data.json"
  "formato": "JSON",
  "total_clientes": 7267,
  "variaveis_por_cliente": 21,
}
```
## 🚀 Como Executar

### 📌 Opção 1: Google Colab 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seu-usuario/telecom-churn-analysis/blob/main/analise_churn.ipynb)

1. Clique no botão **"Open in Colab"** acima
2. Faça login com sua conta Google
3. Clique em **"Runtime" > "Run all"** para executar todo o notebook
4. Para salvar suas alterações:
   - **File > Save a copy in Drive**

### 💻 Opção 2: Execução Local

#### Pré-requisitos
- Python 3.8+
- Jupyter Notebook

#### Passo a passo:
1. Clique em "Code" > "Download ZIP" no GitHub
2. Extraia o arquivo ZIP em sua máquina
3. Na pasta em que foi extraido o arquivo, clique com botão direito e em `Abrir no Terminal`
4. No Terminal digite: `jupyter notebook`
5. Clique no arquivo `Analise_Churn_TeleconX.ipynb`
6. Clique em **"Runtime" > "Run all"** para executar todo o notebook
