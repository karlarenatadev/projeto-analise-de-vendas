# 📊 Análise de Vendas de Loja

Este projeto é uma análise exploratória de dados (EDA) de um conjunto de dados de vendas de uma loja. O objetivo principal é identificar padrões de compra, entender o comportamento dos clientes e extrair insights que possam guiar decisões estratégicas de negócio.

## 🎯 Questões de Negócio Analisadas

A análise foi conduzida para responder às seguintes perguntas:

1.  **Análise de Produtos:**
    * Quais são os produtos mais vendidos em termos de quantidade?
    * Quais produtos e subcategorias geram o maior faturamento?
    * Qual a relação entre o volume de vendas e a receita gerada?

2.  **Análise de Clientes:**
    * Qual é o segmento de cliente mais valioso para a loja?
    * De quais estados e regiões vêm as maiores vendas?

3.  **Análise Sazonal:**
    * Existe alguma sazonalidade nas vendas ao longo do ano?
    * Como essa sazonalidade se comporta para as diferentes categorias de produtos?

## 🚀 Principais Descobertas e Insights

Com base na análise, foram extraídos os seguintes insights estratégicos:

* **Volume vs. Faturamento:** A categoria **"Material de Escritório"** domina em volume de vendas, atuando como um forte "produto de tráfego". No entanto, a subcategoria **"Móveis"** (especificamente mesas) lidera em faturamento, sendo um "produto de valor".
* **Perfil do Cliente:** O segmento **"Consumer" (Consumidor Final)** é o mais lucrativo, representando a maior fatia da receita.
* **Foco Geográfico:** As vendas estão fortemente concentradas nos estados da **Califórnia** e **Nova Iorque**, indicando mercados-chave para a empresa.
* **Padrões Sazonais:** As vendas atingem picos nos meses de **setembro, novembro e dezembro**. A análise cruzada revelou que "Tecnologia" e "Móveis" impulsionam as vendas no final do ano, enquanto "Material de Escritório" possui uma demanda mais constante.

## 🛠️ Ferramentas e Metodologia

* **Linguagem:** Python 3
* **Bibliotecas:**
    * `pandas` para manipulação e análise dos dados.
    * `matplotlib` e `seaborn` для criação das visualizações.
* **Ambiente:** Jupyter Notebook (`analise-de-vendas.ipynb`)

A análise seguiu um processo estruturado de limpeza de dados, seguido por análises descritivas e cruzamento de variáveis para aprofundar os insights.

## 📈 Visualizações Geradas

O projeto inclui diversos gráficos para ilustrar as descobertas, tais como:
* Gráficos de barras para faturamento por subcategoria, segmento e estado.
* Gráfico de linhas para análise de sazonalidade.
* Gráfico de barras empilhadas para faturamento por estado e categoria.
* Mapa de calor (heatmap) para cruzar faturamento entre segmento e categoria.

## 📋 Como Utilizar o Projeto

Para executar esta análise em seu ambiente local, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
    ```

2.  **Instale as dependências:**
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```

3.  **Execute o Jupyter Notebook:**
    Abra o arquivo `analise-de-vendas.ipynb` em seu ambiente Jupyter e execute as células.
