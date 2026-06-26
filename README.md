# 📊 Desafio Extra - Hotel Booking Demand

> Projeto de análise exploratória e modelagem preditiva para estimar cancelamentos de reservas no dataset Hotel Booking Demand.

**Autor:** Jonathan Euzébio Boza

## ✨ Resumo rápido

Este projeto analisa a base [hotel_bookings.csv](hotel_bookings.csv) para identificar padrões ligados ao cancelamento de reservas e construir um modelo preditivo para a variável `is_canceled`.

## 📌 Resultados

| Métrica | Valor |
| --- | --- |
| Acurácia otimizada | 0.8307 |
| F1 da classe cancelada | 0.7205 |
| Recall da classe cancelada | 0.7935 |
| ROC AUC | 0.9072 |

## 🧩 Arquivos do projeto

- [Desafio Extra - Hotel Booking Demand.ipynb](Desafio%20-%20Hotel%20Booking%20Demand.ipynb): notebook com preparação dos dados, EDA, modelagem e avaliação.
- [hotel_bookings.csv](hotel_bookings.csv): base usada no projeto.
- [README.md](README.md): visão geral da solução e resultados.

## 🛠️ O que foi feito

- Compreensão da base e definição da variável-alvo.
- Limpeza e preparação dos dados.
- Análise exploratória com foco em cancelamento, tipo de hotel, lead time e tipo de depósito.
- Modelagem preditiva com pipeline de pré-processamento e classificação.
- Ajuste de limiar para melhorar a detecção da classe cancelada.

## 🚀 Como executar

1. Abra o arquivo [Desafio Extra - Hotel Booking Demand.ipynb](Desafio%20-%20Hotel%20Booking%20Demand.ipynb) no VS Code ou no Jupyter.
2. Execute as células em ordem.
3. Para revisar os dados, abra também [hotel_bookings.csv](hotel_bookings.csv).

## ✅ Resultado final

O modelo final atingiu um bom equilíbrio entre desempenho geral e detecção de cancelamentos, com foco em um problema real de classificação binária desbalanceada.
