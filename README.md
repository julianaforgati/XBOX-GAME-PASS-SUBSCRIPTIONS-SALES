# 🎮 Dashboard Gerencial de Assinaturas Xbox

## 📌 Visão Geral
Este projeto consiste na criação de um **dashboard gerencial de assinaturas Xbox**, desenvolvido em **Microsoft Excel**, com o objetivo de transformar dados brutos de assinaturas em **informações visuais claras, objetivas e úteis para a gestão**.

O dashboard foi pensado para apoiar a **análise do desempenho da base de assinantes**, com foco em **crescimento, monetização, composição dos planos e impacto de add-ons e cupons**.

---

## 🎯 Objetivo do Projeto
- Organizar e estruturar dados de assinaturas digitais
- Criar indicadores gerenciais claros e defensáveis
- Analisar a composição da base de assinantes
- Avaliar a monetização por plano e add-ons
- Mensurar o impacto de cupons e descontos
- Visualizar a evolução das assinaturas ao longo do tempo
- Apoiar a tomada de decisão gerencial

---

## 🏢 Contexto
Os dados utilizados representam uma **base fictícia de assinaturas Xbox**, criada exclusivamente para fins educacionais e de portfólio, simulando um cenário real de gestão de serviços por assinatura.

Não há informações de cancelamento ou churn na base; portanto, o projeto é focado em **crescimento, composição e monetização**.

---

## 📁 Base de Dados

### 📊 Descrição Geral
A base contém informações sobre assinantes, planos contratados, valores pagos, add-ons adquiridos e descontos aplicados.

### 🧾 Campos Utilizados

| Coluna | Descrição |
|------|----------|
| Subscriber ID | Identificador do assinante |
| Name | Nome do assinante |
| Plan | Plano contratado |
| Start Date | Data de início da assinatura |
| Auto Renewal | Indica se a renovação automática está ativa |
| Subscription Price | Valor do plano principal |
| Subscription Type | Tipo de assinatura |
| EA Play Season Pass | Indica se possui EA Play |
| EA Play Season Pass Price | Valor do EA Play |
| Minecraft Season Pass | Indica se possui Minecraft Pass |
| Minecraft Season Pass Price | Valor do Minecraft Pass |
| Coupon Value | Valor de desconto aplicado |
| Total Value | Valor final pago pelo assinante |

---

## 📊 Dashboard Gerencial

O dashboard foi desenvolvido em uma aba única (**Dashboard**), priorizando **clareza visual, hierarquia da informação e leitura rápida**, características essenciais para uso gerencial.

### 🔹 KPIs Principais
- Total de Assinantes
- Receita Total
- Ticket Médio por Assinante
- % de Assinaturas com Renovação Automática
- % de Assinantes com Add-ons

### 🔹 Análises Apresentadas
- Evolução mensal de novas assinaturas (baseado na data de início)
- Distribuição de assinantes por plano
- Receita por plano
- Análise de add-ons (EA Play e Minecraft)

---

## 🛠️ Ferramentas Utilizadas
- **Microsoft Excel**
  - Tabelas estruturadas
  - Tabelas Dinâmicas
  - Gráficos gerenciais
  - Segmentações de dados
- **GitHub**
  - Versionamento
  - Documentação do projeto

---

## ▶️ Instruções para Reprodução

1. Clone o repositório:

git clone https://github.com/seu-usuario/dashboard-gerencial-xbox.git

2. Abra o arquivo do dashboard:

Copiar código
dashboard/dash.xlsx

3. No Excel:

A base de dados deve estar estruturada como Tabela

As métricas são calculadas via Tabelas Dinâmicas

Os gráficos e KPIs são atualizados automaticamente ao alterar filtros ou segmentações


👤 Autora
Juliana Forgati

Projeto desenvolvido como parte de um portfólio de Análise de Dados e Visualização, com foco em dashboards gerenciais e apoio à tomada de decisão baseada em dados.
