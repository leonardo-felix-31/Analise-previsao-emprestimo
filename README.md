# 📊 Projeto de Previsão de Concessão de Empréstimos

Este projeto tem como objetivo analisar dados históricos de pedidos de empréstimos e construir um modelo preditivo capaz de indicar a probabilidade de aprovação ou recusa de um novo pedido. A análise considera características do solicitante como renda, histórico de crédito, educação, entre outros.

---

## 🧠 Objetivos do Projeto

- Entender os fatores que influenciam na aprovação de empréstimos.
- Realizar análise exploratória de dados (EDA) para identificação de padrões.
- Tratar valores ausentes e outliers.
- Criar e comparar modelos de machine learning.
- Avaliar métricas de performance e pontuação entre cada modelo.

---

## 🗂️ Estrutura do Projeto

- `Análise Exploratória`: distribuição de variáveis, correlação e relação com o target.
- `Limpeza de Dados`: tratamento de nulos e outliers.
- `Feature Engineering`: conversão de variáveis categóricas, normalização, balanceamento.
- `Modelagem Preditiva`: Logistic Regression, Decision Tree, Random Forest, KNN e MLP.
- Avaliamos os modelos com os métodos best_params (melhores parametros) e best_score (Pontuação).

---

## 🔍 Principais Insights
- A variável renda é a mais significativa dos dados na hora de conceder empréstimo.
- Solicitantes com histórico de crédito positivo têm alta chance de aprovação.
- Pessoas casadas e com educação superior têm maior taxa de aprovação.
- A variável `LoanAmount` apresenta distribuição assimétrica e foi normalizada.

---

## 🤖 Modelos Utilizados

| Modelo             | Acurácia | Observações                            |
|------------------- |----------|----------------------------------------|
| Regressão Logística| ~87%     | Simples e interpretável                |
| Decision Tree      | ~87%     | Boa para entender regras               |
| Random Forest      | ~89%     | Melhor desempenho                      |
| KNN                | ~88%     | Predição mais rapida                   |
| MLP                | ~87%     | Maior complexidade                     |

---

## 📁 Tecnologias Utilizadas

- Python 3.10
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 🏁 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-emprestimo.git
