# ☕ Projeto de Análise de Dados — Rede de Cafeterias

## 📊 Visão Geral

Este projeto tem como objetivo transformar dados operacionais de uma rede de cafeterias em **insights estratégicos**, utilizando técnicas de análise descritiva, diagnóstica, preditiva e prescritiva.

A abordagem aplicada permite não apenas entender o passado, mas também **prever cenários futuros e orientar decisões de negócio**.

---

## Objetivo de Negócio

* Identificar os principais drivers de faturamento
* Compreender o comportamento das vendas ao longo do tempo
* Prever demanda futura
* Apoiar decisões estratégicas baseadas em dados

---

# 1. Análise Descritiva — O que aconteceu?

A análise descritiva permitiu uma visão geral do desempenho da rede.

📌 (aqui gráfico de faturamento ao longo do tempo)

📌 (aqui gráfico de volume de vendas)

📌 (aqui gráfico de produtos mais vendidos)

### Insights:

* Identificação dos produtos com maior volume e impacto no faturamento
* Distribuição de receita ao longo do tempo
* Padrões iniciais de comportamento de vendas

---

# 2. Análise Diagnóstica — Por que aconteceu?

Nesta etapa, foram investigadas as causas dos padrões observados.

📌 (aqui gráfico de comparação entre períodos)

📌 (aqui gráfico por produto/categoria)

### Insights:

* Diferenças significativas entre períodos de alta e baixa demanda
* Produtos com maior contribuição para o faturamento
* Indícios de fatores que influenciam variações nas vendas

---

# 3. Análise Preditiva — Série Temporal

Foi aplicada análise de **séries temporais**, com decomposição em:

* Tendência (Trend)
* Sazonalidade (Seasonality)
* Ruído (Residual)

📌 (aqui gráfico da série temporal original)

📌 (aqui gráfico da tendência)

📌 (aqui gráfico da sazonalidade)

📌 (aqui gráfico da dessazonalização)

---

## Avaliação do Modelo

📌 (aqui imagem com MAPE e RMSE)

### Métricas:

* **MAPE: 8,64%**
* **RMSE: R$ 363,84**
* Intervalo observado:

  * Mín: R$ 2.037,10
  * Máx: R$ 6.403,91

---

## Interpretação do Erro

* O erro médio percentual de **8,64%** indica boa precisão do modelo
* Em termos financeiros, o erro médio é de aproximadamente **R$ 363**, o que é relativamente baixo considerando o intervalo de faturamento
* Isso demonstra que o modelo é confiável para suporte à decisão

---

## Insights Preditivos

* Identificação de tendência de comportamento das vendas
* Presença de padrões sazonais relevantes
* Capacidade de antecipar períodos de maior e menor demanda

---

# 4. Análise Prescritiva — O que fazer?

Foi aplicado um **modelo de regressão linear** para identificar os fatores que impactam o faturamento.

📌 (aqui imagem da tabela de regressão)

---

## Principais Resultados

* **Produtos únicos (+)** → impacto positivo no faturamento
* **Preço médio (-)** → impacto negativo relevante
* **Categorias (-)** → possível excesso de complexidade
* Variáveis não significativas foram desconsideradas na tomada de decisão

---

## Interpretação de Negócio

* Aumentar diversidade de produtos pode impulsionar receita
* A elevação de preços pode reduzir o volume vendido
* Expansão de categorias deve ser feita com cautela

---

# Proposta de Ações

* Aumentar oferta de produtos estratégicos
* Ajustar preços com base na sensibilidade do cliente
* Planejar estoque e operação com base na sazonalidade
* Intensificar ações comerciais em períodos de baixa demanda
* Utilizar previsões para planejamento operacional

---

# O que evitar

* Aumentos de preço sem análise de impacto
* Expansão descontrolada de categorias
* Ignorar padrões sazonais

---

# 📌 Conclusão

O projeto demonstra a aplicação prática de análise de dados para geração de valor em um contexto de negócio real.

A combinação de análise descritiva, diagnóstica, preditiva e prescritiva permite:

* Melhor compreensão do desempenho
* Antecipação de cenários
* Tomada de decisão mais assertiva

---

# Próximos Passos

* Implementação de modelos preditivos mais avançados
* Automação das análises
* Construção de dashboards interativos
* Monitoramento contínuo dos KPIs

---

# Ferramentas

* Google Sheets
* Análise de Séries Temporais
* Regressão Linear
* Visualização de Dados

---
