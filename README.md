# 📊 Análise Estratégica de Desempenho - Alura Store

![Badge Concluído](http://img.shields.io/static/v1?label=STATUS&message=CONCLUÍDO&color=GREEN&style=for-the-badge)
![Badge Python](http://img.shields.io/static/v1?label=Tech&message=PYTHON&color=blue&style=for-the-badge)
![Badge Pandas](http://img.shields.io/static/v1?label=Lib&message=PANDAS&color=150458&style=for-the-badge)

## 💼 Descrição do Projeto

Este projeto simula um desafio real de **Business Intelligence**. O objetivo foi auxiliar o CEO da *Alura Store* (uma rede varejista fictícia) a tomar uma decisão estratégica de desinvestimento.

A partir de dados brutos de vendas, logística e avaliações, realizei uma análise exploratória para identificar qual das 4 unidades da rede apresentava a menor eficiência operacional e deveria ser vendida para financiar um novo empreendimento.

## 🎯 Objetivo
Identificar, através de dados quantitativos e qualitativos, a loja com pior performance relativa, considerando:
* Faturamento Total;
* Volume de Vendas;
* Satisfação do Cliente (NPS/Avaliações);
* Custo Logístico (Frete).

---

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem base para análise.
* **Pandas:** Carregamento de dados (ETL), limpeza e manipulação de DataFrames.
* **Matplotlib:** Visualização de dados para criação de gráficos comparativos.
* **Jupyter Notebook:** Ambiente de desenvolvimento e documentação.

---

## 🔍 Principais Insights da Análise

Durante a exploração dos dados, levantei pontos cruciais que direcionaram a tomada de decisão:

### 💰 1. Performance Financeira (Faturamento)
A métrica principal de decisão. Ao consolidar as vendas, identificou-se um *gap* de performance:
* **Loja 1 (Líder):** R$ 1.534.509,12
* **Loja 4 (Menor Receita):** R$ 1.384.497,58

> **Insight:** A Loja 4 arrecada cerca de **R$ 150.000,00 a menos** que a líder, indicando ineficiência comercial.

### ⭐ 2. Qualidade Percebida (Avaliações)
Havia a hipótese de que a loja com pior venda teria o pior atendimento. **Os dados refutaram isso.**
* Média geral das lojas: ~4.0
* A análise mostrou uma **homogeneidade** entre as filiais.

> **Conclusão:** O problema da Loja 4 **não é** a qualidade do serviço ou do produto, visto que há um empate técnico na satisfação do cliente.

### 🚚 3. Eficiência Logística (Frete)
Os custos de frete variaram pouco (R$ 31,00 - R$ 35,00).
* A Loja 4 possui um frete competitivo (faixa inferior), mas isso não se traduziu em vendas.
* Isso isola o problema: ter frete barato não está salvando a operação da Loja 4.

---

## 💡 Conclusão e Recomendação

Com base na análise de dados, a recomendação oficial para o *stakeholder* é a **venda da Loja 4**.

### ⚖️ Justificativa da Decisão:
1.  **Menor Retorno Financeiro:** É a unidade com o menor volume de receita (R$ 1.38 Mi), consistentemente atrás das concorrentes internas.
2.  **Problema Estrutural:** O fato de ter boas avaliações e frete competitivo, mas ainda assim vender pouco, sugere problemas estruturais de localização ou demanda de mercado que dificilmente serão resolvidos a curto prazo.
3.  **Custo de Oportunidade:** Vender a unidade menos eficiente libera capital para investimentos com maior potencial de retorno.

---

## 📈 Visualizações

<img width="659" height="393" alt="image" src="https://github.com/user-attachments/assets/362a2b16-cad2-46a1-85db-a8966afec3ff" />
*Comparativo de faturamento demonstrando o desempenho inferior da Loja 4.*

---

## 🙋‍♂️ Autor

Feito por Julio Freitas.
Entre em contato!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juliofrs) 
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:juliofreitaspro@gmail.com)
