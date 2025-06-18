# projeto_an-lise_de_dados
# projeto_an-lise_de_dados
# 📊 Análise de Vendas com Python

Este projeto realiza a análise exploratória de uma base de dados de vendas, utilizando as bibliotecas **Pandas**, **NumPy** e **Plotly Express** para gerar insights visuais sobre o desempenho comercial, categorizado por produtos, marcas, regiões e tempo.

## 🗂️ Dados Utilizados

- Arquivo: `Base de Vendas.xlsx`
- A base contém informações como:
  - Data da Venda
  - Quantidade
  - Valor da Venda
  - Categoria e Marca do Produto
  - Nome da Loja
  - UF da Compra

## ⚙️ Funcionalidades

### 1. **Pré-processamento e Limpeza de Dados**
- Cálculo do valor final da venda (`Quantidade` × `Valor da Venda`)
- Conversão de datas para o formato `Ano-Mês`
- Remoção de colunas desnecessárias para a análise

### 2. **Análise Quantitativa por Categoria**
- Quantidade de vendas agrupadas por categoria de produto
- Visualização: Gráfico de barras

### 3. **Faturamento por Categoria**
- Agrupamento dos dados para somar o faturamento total por categoria
- Visualização: Gráfico de barras colorido com intensidade baseada no valor de faturamento

### 4. **Faturamento por Marca**
- Análise de faturamento total por marca de produto
- Visualização: Gráfico de barras

### 5. **Faturamento ao Longo do Tempo**
- Faturamento total agrupado por mês (`AnoMes`)
- Visualização: Gráfico de linha com marcadores

### 6. **Faturamento por Região**
- Análise do valor total de vendas por unidade federativa (`UF da Compra`)
- Visualização: Gráfico de barras

## 📈 Tecnologias e Bibliotecas

- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Plotly Express](https://plotly.com/python/plotly-express/)
- [Jupyter Notebook](https://jupyter.org/) (opcional para execução interativa)

## ▶️ Como Executar

1. Certifique-se de ter o Python instalado.
2. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas plotly openpyxl numpy

## 📌 Observações

- O código utiliza **arredondamento para cima** (`np.ceil`) no cálculo do valor final da venda.
- A análise **ignora colunas** como `Nome do Produto` e `Nome da Loja`, focando apenas nas dimensões mais relevantes para o faturamento.

## 📎 Autor

Este projeto foi desenvolvido para **fins de estudo** e **demonstração de análise de dados com Python**.  
Sinta-se à vontade para **adaptar conforme a sua necessidade**.
