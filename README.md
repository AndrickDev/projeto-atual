# Análise Exploratória de Dados - Risco de Crédito

Este projeto realiza uma análise exploratória completa sobre o conjunto de dados `UCI_Credit_Card.csv`, com o objetivo de investigar padrões comportamentais de clientes e sua relação com a inadimplência no pagamento de empréstimos.

## 📊 Objetivo
Explorar, entender e visualizar os dados para extrair insights que possam apoiar modelos preditivos de risco de crédito.

## 🧠 Técnicas Utilizadas

- Limpeza e tratamento de dados
- Análise estatística descritiva
- Visualização de dados com `matplotlib` e `seaborn`
- Análise de correlação entre variáveis
- Comparação de variáveis categóricas e numéricas com o target (`default.payment.next.month`)

## 📁 Dados

- Fonte: [UCI Machine Learning Repository - Default of Credit Card Clients Dataset](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)
- Total de registros: 30.000
- Variáveis: 23 colunas incluindo atributos financeiros, demográficos e comportamento de pagamento

## 🔍 Principais Insights

- Identificação das variáveis mais correlacionadas com a inadimplência
- Análise de comportamento de pagamento por sexo, escolaridade e faixa etária
- Tendências de limite de crédito versus pagamentos atrasados

## 🚀 Próximos Passos

- Aplicação de modelos de classificação para prever inadimplência
- Tuning de hiperparâmetros para melhorar performance
- Criação de dashboard interativo com Streamlit ou Dash

## 🧰 Tecnologias

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Jupyter Notebook
