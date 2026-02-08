📊 Análise de Vendas de Suplementos - Excel Dashboard
Projeto completo de análise exploratória de dados utilizando Microsoft Excel com foco em vendas de suplementos alimentares.

---

## Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Objetivos](#-objetivos)
- [Base de Dados](#-base-de-dados)
- [Análises Realizadas](#-análises-realizadas)
- [Principais Insights](#-principais-insights)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Reproduzir](#-como-reproduzir)
- [Resultados Visuais](#-resultados-visuais)

---

## Sobre o Projeto

Este projeto apresenta uma análise completa de dados de vendas de uma empresa de suplementos alimentares, utilizando funcionalidades avançadas do Microsoft Excel como **Tabelas Dinâmicas**, **Gráficos Interativos**, **Fórmulas Estatísticas** e **Dashboards**.

O objetivo principal foi transformar dados brutos de vendas em **insights acionáveis** para tomada de decisão estratégica.

---

## Objetivos

- ✅ Analisar o desempenho de vendas ao longo do ano
- ✅ Identificar os produtos mais vendidos (Análise 80/20)
- ✅ Mapear a distribuição geográfica de clientes
- ✅ Avaliar custos de frete e sua relação com o faturamento
- ✅ Analisar categorias de produtos mais relevantes
- ✅ Calcular ticket médio e variações mensais
- ✅ Criar visualizações interativas para apresentação de resultados

---

## Base de Dados

### Estrutura dos Dados

A base contém **1.043 registros** de pedidos com as seguintes colunas:

| Campo | Descrição | Tipo |
|-------|-----------|------|
| **DATA PEDIDO** | Data da realização do pedido | Data |
| **CÓDIGO** | Código único do produto | Numérico |
| **PRODUTO** | Nome do produto | Texto |
| **CATEGORIA** | Categoria do produto | Texto |
| **VALOR** | Preço unitário do produto | Monetário |
| **QUANTIDADE** | Quantidade vendida | Numérico |
| **VALOR TOTAL** | Valor total da venda | Monetário |
| **ESTADO** | Estado do comprador | Texto |
| **FRETE** | Custo do frete | Monetário |
| **FORNECEDOR** | Fornecedor do produto | Texto |
| **NF** | Número da Nota Fiscal | Texto |
| **STATUS** | Status do pedido | Texto |

### Métricas Gerais

- 📦 **Total de Itens Vendidos:** 9.085 unidades
- 💰 **Faturamento Total:** R$ 667.391,80
- 🚚 **Custo Total de Frete:** R$ 64.466,90
- 📄 **Notas Fiscais Emitidas:** 1.043
- 🏢 **Fornecedores Ativos:** 9
- 📊 **Ticket Médio:** R$ 219,32
- 💵 **Valor Médio Unitário:** R$ 73,23

---

## Análises Realizadas

### **Análise Financeira Geral**

#### Principais Métricas:
- **Valor Total de Vendas:** R$ 667.391,80
- **Valor Médio de Vendas:** R$ 219,32
- **Frete Total:** R$ 64.466,90
- **Frete Médio:** R$ 21,19

#### Percentual de Frete sobre Vendas:
- **10%** do valor total das vendas é destinado ao frete
- Relação consistente entre frete e valor do produto

---

### **Top 10 Produtos Mais Vendidos**

Aplicando o **Princípio de Pareto (80/20)**, identificamos os produtos que geram maior impacto:

| Posição | Produto | Qtd. Vendida | Faturamento | % do Total |
|---------|---------|--------------|-------------|------------|
| 1º | Whey Isolado Baunilha 900g | 118 | R$ 22.408,20 | 20,86% |
| 2º | Shake Proteico Chocolate 400g | 130 | R$ 9.087,00 | 8,46% |
| 3º | Proteína de Arroz Integral 900g | 127 | R$ 17.767,30 | 16,54% |
| 4º | Multivitamínico A-Z 60 cápsulas | 124 | R$ 4.327,60 | 4,03% |
| 5º | Maltodextrina Uva 1kg | 148 | R$ 2.945,20 | 2,74% |
| 6º | Hipercalórico Chocolate 3kg | 118 | R$ 16.508,20 | 15,37% |
| 7º | Creatina Monohidratada 300g | 129 | R$ 11.597,10 | 10,80% |
| 8º | Creatina Monohidratada 100g | 118 | R$ 4.708,20 | 4,38% |
| 9º | CLA (Ácido Linoleico) 1000mg 60 caps | 121 | R$ 6.037,90 | 5,62% |
| 10º | Café Termogênico em pó 220g | 118 | R$ 4.708,20 | 4,38% |

**💡 Insight:** Os **10 produtos** representam **R$ 107.396,60** em vendas, correspondendo a uma parcela significativa do faturamento total.

---

### **Análise Geográfica - Estados que Mais Compraram**

| Estado | Quantidade de Pedidos |
|--------|-----------------------|
| 🥇 **São Paulo** | 404 |
| 🥈 **Mato Grosso** | 399 |
| 🥉 **Alagoas** | 391 |
| 4º Rio Grande do Sul | 381 |
| 5º Pernambuco | 376 |
| 6º Amapá | 372 |
| 7º Rio de Janeiro | 367 |
| 8º Sergipe | 367 |
| 9º Espírito Santo | 362 |
| 10º Ceará | 380 |

**Total de Pedidos:** 3.799

**💡 Insight:** São Paulo lidera em volume de pedidos, mas a distribuição é relativamente equilibrada entre os estados, indicando uma penetração nacional.

---

### **Análise de Categorias de Produtos**

| Categoria | Quantidade Vendida |
|-----------|--------------------|
| 🥇 **Aminoácidos** | 1.128 |
| 🥈 **Pré-Treinos e Energéticos** | 863 |
| 🥉 **Carboidratos e Hipercalóricos** | 792 |
| 4º Termogênicos e Emagrecimento | 681 |
| 5º Proteínas | 559 |
| 6º Substitutos de Refeição e Shakes | 501 |
| 7º Colágeno e Saúde Articular | 417 |
| 8º Adaptógenos e Fitoterápicos | 291 |
| 9º Superfoods / Algas | 203 |
| 10º Detox | 177 |

**💡 Insight:** **Aminoácidos** são a categoria mais vendida, seguida por pré-treinos, indicando um público focado em performance esportiva.

---

### **Evolução de Vendas por Mês**

#### Faturamento Mensal:

| Mês | Valor Total | Variação |
|-----|-------------|----------|
| Janeiro | R$ 29.849,40 | - |
| Fevereiro | R$ 27.794,80 | -6,88% |
| Março | R$ 32.183,90 | +15,79% |
| Abril | R$ 36.476,40 | +13,34% |
| Maio | R$ 36.204,00 | -0,75% |
| Junho | R$ 38.099,10 | +5,23% |
| Julho | R$ 39.405,50 | +3,43% |
| Agosto | R$ 50.071,50 | +27,07% 📈 |
| Setembro | R$ 53.223,10 | +6,30% |
| Outubro | R$ 64.470,00 | +21,13% 📈 |
| Novembro | R$ 80.990,70 | +25,64% 📈 |
| Dezembro | R$ 178.623,40 | +120,56% 🚀 |

**💡 Insight:** 
- Crescimento exponencial no **segundo semestre**
- **Dezembro** representa **26,76%** do faturamento anual
- Sazonalidade clara: vendas aumentam significativamente entre agosto e dezembro

---

### **Quantidade de Itens Comprados por Mês**

| Mês | Quantidade de Itens |
|-----|---------------------|
| Janeiro | 439 |
| Fevereiro | 400 |
| Março | 452 |
| Abril | 458 |
| Maio | 509 |
| Junho | 525 |
| Julho | 575 |
| Agosto | 670 |
| Setembro | 712 |
| Outubro | 874 |
| Novembro | 1.043 |
| Dezembro | 2.428 🚀 |

**Total:** 9.085 itens

**💡 Insight:** O volume de vendas em **dezembro** é **2,3x maior** que a média mensal, reforçando o efeito sazonal de fim de ano.

---

### **Evolução dos Custos de Frete**

#### Frete Mensal:

| Mês | Frete Total | % sobre Vendas |
|-----|-------------|----------------|
| Janeiro | R$ 3.530,53 | 11,83% |
| Fevereiro | R$ 2.731,96 | 9,83% |
| Março | R$ 3.275,93 | 10,18% |
| Abril | R$ 3.297,28 | 9,04% |
| Maio | R$ 3.450,10 | 9,53% |
| Junho | R$ 4.039,71 | 10,60% |
| Julho | R$ 4.094,49 | 10,39% |
| Agosto | R$ 4.613,39 | 9,21% |
| Setembro | R$ 5.279,04 | 9,92% |
| Outubro | R$ 6.374,99 | 9,89% |
| Novembro | R$ 7.310,51 | 9,03% |
| Dezembro | R$ 16.468,97 | 9,22% |

**💡 Insight:** 
- O percentual de frete se mantém **consistente** entre **9-11%** do faturamento
- Pico absoluto em **dezembro** acompanha o aumento de vendas
- Eficiência logística mantida mesmo em alta demanda

---

### **Ticket Médio Mensal**

| Mês | Ticket Médio | Variação vs Média Geral (R$ 219,32) |
|-----|--------------|-------------------------------------|
| Janeiro | R$ 193,83 | -11,62% ⬇️ |
| Fevereiro | R$ 213,81 | -2,51% |
| Março | R$ 213,14 | -2,82% |
| Abril | R$ 235,33 | +7,30% ⬆️ |
| Maio | R$ 212,86 | -2,95% |
| Junho | R$ 215,25 | -1,86% |
| Julho | R$ 204,17 | -6,91% |
| Agosto | R$ 227,60 | +3,78% ⬆️ |
| Setembro | R$ 219,03 | -0,13% |
| Outubro | R$ 215,62 | -1,69% |
| Novembro | R$ 232,07 | +5,81% ⬆️ |
| Dezembro | R$ 222,72 | +1,55% |

**💡 Insight:** 
- Ticket médio **estável** ao longo do ano (variação de ±10%)
- **Abril, Agosto e Novembro** apresentam os maiores tickets médios
- Janeiro tem o menor ticket médio (período pós-festas)

---

## Principais Insights

### Estratégicos:

1. **Sazonalidade Forte:** O segundo semestre concentra **70%** do faturamento anual, com pico em dezembro
2. **Princípio 80/20:** 10 produtos representam aproximadamente **16%** do faturamento
3. **Eficiência Logística:** Frete mantém-se em ~10% mesmo com aumento de demanda
4. **Distribuição Geográfica:** Penetração nacional equilibrada, com leve concentração em SP e MT
5. **Categorias de Destaque:** Aminoácidos e Pré-Treinos dominam as vendas

### Operacionais:

1. **Planejamento de Estoque:** Necessário reforço no segundo semestre (ago-dez)
2. **Gestão de Fornecedores:** 9 fornecedores ativos, com distribuição equilibrada
3. **Ticket Médio Estável:** Produto mix consistente ao longo do ano
4. **Oportunidade de Crescimento:** Primeiro semestre apresenta potencial de expansão

---

## Tecnologias Utilizadas

### Microsoft Excel
- **Tabelas Dinâmicas** - Análise multidimensional de dados
- **Gráficos Dinâmicos** - Visualização interativa
- **Fórmulas Avançadas:**
  - `SOMASE`, `MÉDIA`, `MÁXIMO`, `ÍNDICE`
  - Cálculos percentuais e estatísticos
- **Formatação Condicional** - Destaque visual de dados
- **Segmentação de Dados** - Filtros interativos

### Técnicas de Análise
-  Análise de Pareto (80/20)
-  Análise de Tendências Temporais
-  Análise de Distribuição Geográfica
-  Cálculos de KPIs (Ticket Médio, Percentuais, Variações)
-  Dashboard Interativo

---

## Resultados Visuais

### Dashboards Criados:

1. **Dashboard Principal:** Visão geral das métricas de negócio
2. **Análise Temporal:** Evolução de vendas, frete e ticket médio por mês
3. **Análise de Produtos:** Top 10 e distribuição por categoria
4. **Análise Geográfica:** Mapa de calor de vendas por estado
5. **Análise 80/20:** Identificação dos produtos mais estratégicos

### Gráficos Utilizados:

- 📊 Gráficos de Barras Horizontais (comparações)
- 📈 Gráficos de Linhas (tendências temporais)
- 📉 Gráficos de Área (volume acumulado)
- 🥧 Tabelas de Rankings
- 🎯 Cards de KPIs

---


## 🙏 Agradecimentos

- Dados fictícios criados para fins educacionais
- Projeto desenvolvido como parte do portfólio de análise de dados





