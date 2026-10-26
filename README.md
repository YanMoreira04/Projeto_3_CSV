
# 📊 Análise de Dados de Vendas com Python e Pandas

## 📌 Sobre o projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados de vendas utilizando **Python e Pandas**. A partir de uma base de dados em formato CSV, são realizadas etapas de leitura, tratamento, organização e análise das informações para identificar padrões e compreender o desempenho das vendas.

O projeto explora diferentes perspectivas dos dados, como vendas por país, produto, vendedor e período, utilizando agrupamentos, ordenação de resultados e visualizações gráficas.

## 🎯 Objetivos

- Praticar a manipulação e análise de dados com Python.
- Importar e explorar arquivos CSV utilizando Pandas.
- Realizar o tratamento e a conversão de tipos de dados.
- Analisar o desempenho das vendas por diferentes categorias.
- Identificar os produtos e vendedores com melhores resultados.
- Acompanhar a evolução das vendas ao longo do tempo.
- Criar gráficos para facilitar a interpretação dos resultados.

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 📁 Estrutura do projeto

```text
Projeto_3_CSV/
├── Sales.csv
├── main.ipynb
└── README.md
```

## 📂 Sobre os dados

A base de dados contém informações relacionadas às vendas, incluindo vendedores, países, produtos, datas, valores monetários e quantidade de caixas enviadas.

| Coluna | Descrição |
|---|---|
| `Sales Person` | Nome do vendedor responsável pela venda |
| `Country` | País relacionado à venda |
| `Product` | Produto vendido |
| `Date` | Data da venda |
| `Amount` | Valor monetário da venda |
| `Boxes Shipped` | Quantidade de caixas enviadas |

## ⚙️ Análises realizadas

### 1. Importação e exploração dos dados

Leitura do arquivo CSV utilizando Pandas e visualização inicial dos registros.

### 2. Tratamento dos dados

Verificação dos tipos de dados e conversão das datas para o formato datetime.

### 3. Análise de vendas por país

Agrupamento dos dados por país para comparar os valores de vendas.

### 4. Análise de desempenho dos vendedores

Identificação dos vendedores com melhores resultados e comparação dos valores vendidos.

### 5. Análise de vendas por produto

Agrupamento das vendas por produto e criação de gráficos para facilitar a comparação.

### 6. Análise temporal

Análise da evolução das vendas ao longo dos meses e anos por meio de agrupamentos e gráficos de linha.

## 🚀 Como executar o projeto

### Pré-requisitos

- Python 3 instalado
- Jupyter Notebook
- Bibliotecas Pandas e Matplotlib

### 1. Clone o repositório

```bash
git clone https://github.com/YanMoreira04/Projeto_3_CSV.git
```

### 2. Entre na pasta do projeto

```bash
cd Projeto_3_CSV
```

### 3. Instale as dependências

```bash
pip install pandas matplotlib notebook
```

### 4. Execute o Jupyter Notebook

```bash
jupyter notebook
```

### 5. Abra o notebook

Abra o arquivo `main.ipynb` e execute as células em ordem.

**Importante:** mantenha o arquivo `Sales.csv` na mesma pasta do notebook.

## 📚 Aprendizados

Com este projeto, foi possível praticar conceitos importantes de análise de dados, como:

- Manipulação de DataFrames com Pandas.
- Agrupamento de dados utilizando `groupby()`.
- Ordenação e comparação de resultados.
- Conversão e análise de datas.
- Criação de gráficos com Matplotlib.
- Análise exploratória de dados (EDA).

## 💡 Melhorias futuras

- Criar um dashboard interativo com Power BI ou Streamlit.
- Desenvolver indicadores de desempenho (KPIs).
- Comparar o desempenho dos produtos ao longo do tempo.
- Automatizar a limpeza e preparação dos dados.
- Criar visualizações interativas com Plotly.

## 👨‍💻 Autor

**Yan Moreira**

- GitHub: [@YanMoreira04](https://github.com/YanMoreira04)
- Repositório: [Projeto_3_CSV](https://github.com/YanMoreira04/Projeto_3_CSV)

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório!
