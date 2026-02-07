# 📊 Sales Insight: Análise Exploratória de Vendas (EDA)

Este repositório contém uma análise detalhada de um conjunto de dados de vendas no varejo. O projeto utiliza técnicas de **Exploratory Data Analysis (EDA)** para transformar dados brutos em inteligência de negócio, identificando gargalos, oportunidades de crescimento e comportamentos sazonais.

## 🎯 Objetivos da Análise

A análise foi estruturada para responder a pilares estratégicos:

1.  **Performance de Produtos:** Identificação de "produtos de tráfego" (alto volume) vs. "produtos de valor" (alto faturamento).
2.  **Inteligência Geográfica & Segmentação:** Mapeamento de regiões críticas e perfis de clientes mais rentáveis.
3.  **Sazonalidade:** Identificação de tendências temporais para otimização de estoque e campanhas de marketing.

## 🚀 Principais Descobertas e Insights

Os dados revelaram padrões fundamentais para a tomada de decisão:

* **Estratégia de Categoria:** A categoria de **Material de Escritório** é o principal motor de volume, enquanto a subcategoria de **Mesas (Furniture)** é a que mais agrega faturamento individual.
* **Segmento Dominante:** O segmento **Consumer (B2C)** lidera o consumo, representando a maior fatia da receita total.
* **Potencial Geográfico:** As vendas possuem forte concentração nos estados da **Califórnia** e **Nova Iorque**, sugerindo a necessidade de reforçar a logística ou marketing nessas regiões.
* **Ciclos de Vendas:** Há um crescimento acentuado no último trimestre (**setembro a dezembro**). O cruzamento de dados mostra que Tecnologia e Móveis impulsionam as vendas de final de ano, enquanto Materiais de Escritório mantêm uma receita estável.

## 🛠️ Tecnologias e Ferramentas

O projeto foi desenvolvido utilizando o ecossistema de Data Science do Python:

* **Linguagem:** Python 3.x
* **Manipulação de Dados:** `Pandas`
* **Visualização de Dados:** `Matplotlib` e `Seaborn`
* **Ambiente de Desenvolvimento:** `Jupyter Notebook`

## 📉 Visualizações Destacadas

Para facilitar a interpretação dos dados, foram gerados:
* **Gráficos de Barras:** Comparação de faturamento por subcategoria, segmento e estado.
* **Gráficos de Linha:** Evolução mensal das vendas para análise de sazonalidade.
* **Heatmaps:** Cruzamento matricial entre Segmento de Cliente e Categoria de Produto.
* **Barras Empilhadas:** Distribuição de categorias de produtos por estado.

## 📂 Estrutura do Projeto

* `train.csv`: Conjunto de dados brutos contendo o histórico de vendas.
* `analise-de-vendas.ipynb`: Notebook contendo todo o código de limpeza, tratamento e visualização.
* `README.md`: Documentação do projeto.

## 📋 Como Executar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/karlarenatadev/projeto-analise-de-vendas.git](https://github.com/karlarenatadev/projeto-analise-de-vendas.git)
    cd projeto-analise-de-vendas
    ```

2.  **Instale as dependências necessárias:**
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```

3.  **Inicie o ambiente:**
    ```bash
    jupyter notebook
    ```
    Abra o arquivo `analise-de-vendas.ipynb` e execute as células para visualizar a análise.
    jupyter notebook
    ```
    Abra o arquivo `analise-de-vendas.ipynb` e execute as células para visualizar a análise.
