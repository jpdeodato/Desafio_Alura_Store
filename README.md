# Desafio_Alura_Store
Desafio da Formação Fundamentos de Python
# 📊 Análise de Desempenho de Lojas de Varejo

## 📌 Visão Geral
Este projeto tem como objetivo analisar o desempenho de quatro lojas de varejo fictícias a partir de seus dados de vendas. A análise contempla métricas financeiras, comportamento de vendas, satisfação dos clientes e distribuição geográfica, com o intuito de identificar a loja com pior desempenho geral e subsidiar uma possível decisão de encerramento de atividades.

O projeto foi desenvolvido como parte dos estudos em **Análise de Dados com Python**.

---

## 🗂️ Fontes de Dados
Os dados utilizados são arquivos CSV públicos, hospedados no GitHub:

- **Loja 1:**  
  https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv
- **Loja 2:**  
  https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv
- **Loja 3:**  
  https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv
- **Loja 4:**  
  https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv

---

## 🔍 Análises Realizadas
O notebook executa as seguintes análises exploratórias e descritivas:

- Faturamento total por loja
- Vendas e faturamento por categoria de produto
- Média de avaliação das compras (satisfação do cliente)
- Produtos mais e menos vendidos em cada loja
- Frete médio por loja
- Distribuição geográfica das vendas no Brasil

---

## 📈 Visualizações
Para apoiar a análise, foram gerados diversos gráficos, incluindo:

- Comparação entre faturamento total, frete médio e nota média de satisfação por loja
- Proporção de vendas por categoria (gráficos de pizza)
- Top 5 categorias por faturamento em cada loja (gráficos de barras horizontais)
- Mapa do Brasil com a localização das vendas

---

## 🧾 Conclusão
Com base na análise dos dados, a **Loja 4** apresentou o pior desempenho financeiro, com um faturamento total de **R$ 1.384.497,58**, o menor entre as quatro lojas analisadas.

Apesar de possuir o menor frete médio, a Loja 4 apresenta volume de vendas e receita total inferiores às demais. Dessa forma, considerando os indicadores analisados, ela se mostra a principal candidata a um possível encerramento de atividades.

A **Loja 1**, embora apresente a menor média de avaliação de compra, obteve faturamento superior ao da Loja 4, indicando melhor desempenho financeiro geral.

---

## 🛠️ Ferramentas Utilizadas
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
