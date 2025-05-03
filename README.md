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

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/74/Correlation_heatmap.png/640px-Correlation_heatmap.png" alt="Heatmap de Correlação" width="600">

- Solicitantes com histórico de crédito positivo têm alta chance de aprovação.
- Pessoas casadas e com educação superior têm maior taxa de aprovação.
- A variável `LoanAmount` apresenta distribuição assimétrica e foi normalizada.

---

## 🤖 Modelos Utilizados

| Modelo            | Acurácia | Observações                           |
|-------------------|----------|----------------------------------------|
| Regressão Logística | ~81%     | Simples e interpretável                |
| Decision Tree      | ~76%     | Boa para entender regras               |
| Random Forest      | ~83%     | Redução de overfitting                 |
| XGBoost            | **~84%** | Melhor desempenho entre os modelos     |

---

## 📁 Tecnologias Utilizadas

- Python 3.10
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- xgboost

---

## 🏁 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-emprestimo.git
