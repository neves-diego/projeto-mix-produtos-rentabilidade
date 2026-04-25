# Projeto de Análise de Dados  
## Otimização do Mix de Produtos por Rentabilidade (Curva ABC)

## Sobre o Projeto

Este projeto tem como objetivo identificar quais categorias de produtos realmente sustentam a rentabilidade de uma operação comercial, utilizando a metodologia de classificação ABC baseada em lucro.

Muitas empresas avaliam seus produtos apenas pelo faturamento bruto, o que pode levar a decisões equivocadas. Produtos com alto volume de vendas nem sempre geram alta margem de lucro, podendo inclusive comprometer a saúde financeira da operação.

A proposta deste projeto é demonstrar como a análise de dados pode apoiar decisões mais estratégicas, permitindo aumentar a margem líquida sem necessariamente aumentar o volume de vendas.

---

## Problema de Negócio

Produtos com alto faturamento nem sempre são os mais lucrativos.

Essa distorção pode levar empresas a:

- investir em produtos pouco rentáveis
- ocupar estoque com itens de baixo retorno
- comprometer capital de giro
- tomar decisões estratégicas equivocadas

A análise ABC baseada em rentabilidade permite identificar quais produtos devem ser priorizados, otimizados ou revisados.

---

## Fonte de Dados

Foi utilizado o dataset SuperMarket Analysis, disponível publicamente na plataforma Kaggle.

A base contém informações de vendas de supermercado, incluindo:

- categoria de produto
- preço unitário
- quantidade vendida
- receita total
- custo da mercadoria vendida (COGS)
- lucro bruto

A presença da variável COGS permite calcular a rentabilidade real sem necessidade de simulações artificiais.

---

## Ferramentas Utilizadas

- Python
- Pandas
- Google Colab
- Looker Studio
- GitHub

---

## Etapas da Análise

### 1. Coleta de Dados

Download direto do arquivo CSV via Kaggle.

### 2. Limpeza e Tratamento

- padronização de colunas
- verificação de valores nulos
- agrupamento por categoria de produto

### 3. Análise Exploratória (EDA)

- receita total
- custo total
- lucro bruto
- margem média
- participação acumulada no lucro

### 4. Classificação ABC

Aplicação da Curva ABC com base no lucro:

- Priorizar → até 70%
- Otimizar → até 90%
- Revisar → acima de 90%

### 5. Dashboard Executivo

Criação de dashboard estratégico no Looker Studio com foco em tomada de decisão.

---

## Principais Insights

- 4 categorias concentram a maior parte da rentabilidade
- Health and Beauty apresenta alto faturamento, mas baixa rentabilidade
- Faturamento isolado não representa eficiência financeira
- Melhorar o mix de produtos pode aumentar margem sem aumentar vendas

---

## Dashboard

Link do dashboard:
https://datastudio.google.com/s/pdOGN_SIg08

---

## Conclusão

A análise demonstrou que vender mais não significa necessariamente lucrar mais.

A gestão orientada por rentabilidade permite decisões mais inteligentes sobre estoque, fornecedores, precificação e estratégia comercial.

O verdadeiro crescimento está em vender melhor.
