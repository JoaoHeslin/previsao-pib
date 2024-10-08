# Análise de Séries Temporais do PIB do Brasil

Este projeto realiza uma análise de séries temporais do PIB do Brasil utilizando o modelo ARIMA, com o objetivo de prever variações futuras e verificar a adequação do modelo com base no comportamento dos resíduos.

## Análise Realizada

1. **Importação e tratamento dos dados**: Preparação dos dados do PIB.
2. **Modelagem ARIMA**: Busca pelo melhor modelo ARIMA para ajustar a série temporal.
3. **Avaliação do Modelo**: Testes de autocorrelação (Ljung-Box) para avaliar se os resíduos se comportam como ruído branco.

## Resultados

- O modelo identificado foi o **ARIMA(0,0,0)(0,0,1)[10]**.
- O teste de Ljung-Box indicou ausência de autocorrelação significativa nos resíduos.
- O tempo total de ajuste do modelo foi de **0.766 segundos**.

## Conclusão

O modelo ARIMA utilizado foi adequado para a previsão do PIB do Brasil, apresentando resíduos que se comportam como ruído branco, o que indica uma boa adequação do modelo às características da série temporal.
