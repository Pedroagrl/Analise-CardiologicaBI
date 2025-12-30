# KPIs do Projeto — Análise Cardiológica

Este documento descreve os indicadores utilizados nos dashboards do projeto, detalhando sua lógica de cálculo e o objetivo analítico de cada métrica. Os KPIs têm caráter exploratório e não representam diagnóstico clínico.

---

## KPI — % Doença com Sintoma (Dor no Peito)

**Descrição:**  
Percentual de pacientes com doença cardíaca que apresentaram dor no peito como sintoma clínico.

**Numerador:**  
Pacientes com status cardíaco = "Com Doença Cardíaca" e tipo de dor no peito ≠ "Assintomático".

**Denominador:**  
Total de pacientes com doença cardíaca.

**Objetivo Analítico:**  
Avaliar a proporção de casos em que a doença esteve associada a um sintoma clássico, destacando o papel dos sintomas na identificação da condição.

---


## KPI — Taxa de Doença Detectada por ECG Alterado

**Descrição:**  
Percentual de pacientes com doença cardíaca que apresentaram alterações no exame de ECG.

**Numerador:**  
Pacientes com status cardíaco = "Com Doença Cardíaca" e ECG ≠ "Normal".

**Denominador:**  
Total de pacientes.

**Objetivo Analítico:**  
Analisar a contribuição do exame de ECG na identificação de casos de doença cardíaca.

---

## KPI — % Doença Detectada Apenas por ECG

**Descrição:**  
Percentual de pacientes com doença cardíaca que não apresentaram dor no peito, mas tiveram alteração no exame de ECG.

**Numerador:**  
Pacientes com status cardíaco = "Com Doença Cardíaca", tipo de dor no peito = "Assintomático" e ECG ≠ "Normal".

**Denominador:**  
Total de pacientes com doença cardíaca.

**Objetivo Analítico:**  
Evidenciar casos em que o exame eletrocardiográfico foi fundamental para a detecção da doença na ausência de sintomas clínicos.

---
## KPI — Proporção de ECG Grave entre ECGs Alterados

**Descrição:**  
Percentual de exames de ECG classificados como alteração grave entre todos os ECGs alterados.

**Numerador:**  
Pacientes com ECG = "Alteração Grave".

**Denominador:**  
Pacientes com ECG ≠ "Normal".

**Objetivo Analítico:**  
Avaliar a severidade das alterações eletrocardiográficas observadas.

---

## KPI — % Perfusão Anormal

**Descrição:**  
Percentual de pacientes que apresentaram resultado anormal no exame de perfusão cardíaca.

**Numerador:**  
Pacientes com Resultado da Perfusão ≠ "Normal".

**Denominador:**  
Total de pacientes que realizaram o exame de perfusão.

**Objetivo Analítico:**  
Avaliar a frequência de alterações na perfusão miocárdica entre os pacientes examinados.

---

## KPI — % Confirmação por Exames

**Descrição:**  
Percentual de pacientes com doença cardíaca que apresentaram pelo menos um exame diagnóstico alterado (ECG ou perfusão).

**Numerador:**  
Pacientes com status cardíaco = "Com Doença Cardíaca" e (ECG ≠ "Normal" ou perfusão ≠ "Normal").

**Denominador:**  
Total de pacientes com doença cardíaca.

**Objetivo Analítico:**  
Avaliar a proporção de casos em que o diagnóstico da doença foi confirmado por exames clínicos objetivos.
