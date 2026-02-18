# 🍦 Ice Cream Sales ML

Este projeto tem como objetivo prever as vendas de sorvete com base na temperatura do dia, usando Machine Learning.

## 📂 Estrutura
- `inputs/` → contém os dados de entrada (dados.txt).
- `notebooks/` → contém o notebook `modelo.ipynb` com o código de análise e modelagem.
- `README.md` → documentação do projeto.

## 🚀 Passos realizados
1. Criação de dataset simples relacionando temperatura e vendas.
2. Treinamento de um modelo de regressão linear.
3. Visualização dos resultados em gráfico.
4. Registro do modelo com MLflow.

## 📊 Resultados
- O modelo conseguiu prever vendas com base na temperatura.
- Exemplo: para 28°C, previsão ≈ 170 sorvetes.
- Gráfico mostra correlação positiva entre temperatura e vendas.

## 💡 Insights
- Quanto maior a temperatura, maior a demanda.
- Acima de 30°C, a curva de vendas cresce mais rápido.
- Possibilidade de incluir variáveis como chuva, dia da semana e feriados.

## 🔮 Próximos passos
- Testar outros modelos (Random Forest, XGBoost).
- Implementar API com FastAPI para previsões em tempo real.
- Deploy em ambiente de cloud computing.
