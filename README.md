# Pódio Copa 2026 — Previsão com Machine Learning

Projeto de análise de dados e Machine Learning baseado nas estatísticas táticas da Copa do Mundo 2022, usado para projetar um potencial pódio para a Copa de 2026.

## Metodologia

Os dados de 64 partidas da Copa de 2022 foram limpos, transformados em estatísticas por seleção, e usados para treinar um modelo de Random Forest que estima um "potencial tático" — uma pontuação contínua baseada em saldo de gols, eficiência de chutes, precisão de passes e taxa de vitórias.

**Importante:** essa projeção reflete o desempenho tático da Copa de 2022, não uma previsão direta para 2026. Times mudam de elenco, técnico e contexto entre edições — o modelo assume que padrões táticos têm alguma continuidade entre gerações de uma seleção.

## Estrutura do repositório

- `notebook_analise.ipynb` — notebook completo com limpeza de dados, engenharia de features, treinamento do modelo e visualizações
- `ranking_final.csv` — ranking completo de todas as seleções por potencial tático
- `podio_2026.png` — visualização do pódio projetado
- `top7_tabela.png` — tabela com as 7 seleções mais bem posicionadas

## Tecnologias utilizadas

- Python
- pandas, scikit-learn, matplotlib
- Google Colab
- Random Forest Regressor

## Top 7 projetado

| Posição | Seleção | Potencial tático |
|---|---|---|
| 1 | England | 100% |
| 2 | Portugal | 86.9% |
| 3 | France | 86.8% |
| 4 | Netherlands | 84.5% |
| 5 | Spain | 84.3% |
| 6 | Argentina | 81.8% |
| 7 | Brazil | 79.2% |

## Fonte dos dados

Estatísticas detalhadas de todas as partidas da Copa do Mundo FIFA 2022.
