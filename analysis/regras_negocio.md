# Regras de Negócio e Transformações de Dados

Este documento descreve as principais transformações realizadas no conjunto de dados para viabilizar a análise e a construção dos dashboards.

---

## Conversão de Variáveis Binárias

Variáveis originalmente codificadas como 0 e 1 foram convertidas para valores textuais, com o objetivo de melhorar a legibilidade e interpretação visual:

- 0 → Sem Doença Cardíaca  
- 1 → Com Doença Cardíaca

---

- 0 → Feminino
- 1 → Masculino

---

## Criação de Faixa Etária

A variável idade foi categorizada em faixas etárias para facilitar análises comparativas e reduzir a granularidade excessiva dos dados.

As faixas etárias utilizadas foram definidas com base em intervalos regulares.

---

## Classificação dos Resultados de ECG

Os resultados do exame de ECG foram categorizados em:
- Normal
- Alteração Leve
- Alteração Grave

Essa categorização permite analisar não apenas a presença de alteração, mas também sua severidade.

---

## Classificação dos Tipos de dor no Peito

Os resultados dos tipos de dores foram categorizados em:
- Dor Angina Atípica
- Dor Angina Típica
- Dor Assintomático
- Dor Não Anginosa

---
## Classificação das Perfusões

Os resultados dos tipos de perfusões foram categorizados em:
- Normal
- Alteração Reversível
- Alteração Fixa

---
