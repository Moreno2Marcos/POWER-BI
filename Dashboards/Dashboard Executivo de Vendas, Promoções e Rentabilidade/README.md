# Case Técnico — Dashboard Executivo de Vendas, Promoções e Rentabilidade

## Contexto

Este projeto foi desenvolvido como parte de um desafio técnico para uma vaga na área de Power BI. O case simulava o contexto de uma empresa de varejo que comercializa produtos em diferentes lojas, regiões e categorias, com forte investimento em promoções, mas sem clareza suficiente sobre a efetividade dessas ações no resultado do negócio.

O objetivo central do desafio era estruturar uma solução analítica capaz de apoiar a tomada de decisão a partir de três perguntas principais:

- Quais promoções realmente funcionam
- Quais produtos trazem mais resultado
- Se os descontos estão impactando positivamente a receita

## Objetivo da solução

A proposta deste dashboard foi consolidar, em uma visão executiva, indicadores e análises que permitissem avaliar simultaneamente:

- desempenho comercial
- eficiência promocional
- rentabilidade
- contribuição de categorias, subcategorias e produtos

A solução foi construída com foco em clareza analítica, consistência do modelo de dados e aderência ao problema de negócio apresentado no case.

## Escopo desenvolvido

O projeto contemplou as seguintes frentes:

### 1. Modelagem de dados
Foi realizada revisão da estrutura original do modelo, com ajustes para melhorar a consistência entre fato e dimensões, simplificando a navegação analítica e aproximando o desenho de um modelo mais adequado para consumo em Power BI.

### 2. Métricas em DAX
Foram criadas medidas para suportar a análise de vendas, descontos, margem, comparação temporal e participação, permitindo avaliar receita, resultado econômico e eficiência promocional sob diferentes recortes.

### 3. Segurança em nível de linha
Foi implementado RLS dinâmico por país, permitindo restringir a visualização conforme o usuário logado no relatório.

### 4. Front-end executivo
Foi desenvolvido um dashboard em página única com foco em leitura gerencial, reunindo KPIs, análise temporal, comparação entre promoções, detalhamento de produtos e análise por categoria, subcategoria e produto.

## Principais análises presentes no dashboard

- KPIs de vendas líquidas, margem, quantidade vendida, vendas brutas, desconto e custo
- Evolução temporal da receita e do desconto
- Comparação de margem entre promoções e cenário sem desconto
- Ranking de produtos por resultado
- Análise por categoria, subcategoria e produto com alternância de métricas
- Tabela detalhada com foco em margem e vendas líquidas por produto

## Ferramentas e conceitos aplicados

- Power BI
- DAX
- Modelagem dimensional
- RLS dinâmico
- Storytelling com dados
- Design de dashboard executivo

## Aprendizados do projeto

Este case foi importante para reforçar, na prática, pontos como:

- tradução de perguntas de negócio em estrutura analítica
- equilíbrio entre profundidade técnica e objetividade executiva
- importância da escolha correta de métricas para interpretar promoções, receita e rentabilidade
- cuidados com contexto de filtro, RLS e experiência de navegação no dashboard

## Observação

Por se tratar de um case técnico, o projeto foi desenvolvido em um cenário simulado, com foco em demonstrar raciocínio analítico, modelagem, construção de métricas e capacidade de transformar dados em uma interface orientada à decisão.

## Link de acesso ao Dashboard
https://app.powerbi.com/view?r=eyJrIjoiMzM0MjFlYTMtYWU1Zi00NDhlLWE1NWUtZjk4MzViM2VkMzkzIiwidCI6IjUzODhmOWY4LTJmYTktNDlkZS1iN2FlLWY2OGQ2YTMwZDk0OSJ9
