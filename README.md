# Churn de Clientes em Operadora Telefônica

## 🎯 Objetivo

Prever possível churn de clientes, utilizando dados contratuais, pessoais e de serviços em modelos de classificação.

## 🧠 Como fiz o projeto

O projeto foi desenvolvido a partir da unificação de múltiplas bases de dados utilizando a chave customerID, seguida de análise exploratória para identificação de padrões de churn. Realizei o pré-processamento dos dados com tratamento de valores ausentes, engenharia de atributos e criação da variável alvo. Testei diferentes modelos de classificação utilizando pipelines e validação cruzada estratificada. O modelo LightGBM foi selecionado como solução final por apresentar melhor desempenho em ROC-AUC e F1-score.

## 🚀 Tecnologias
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn (pré-processamento, pipelines, validação cruzada e modelos de classificação)
- LightGBM (gradient boosting)

## 📦 Como instalar
```bash
git clone https://github.com/joaostr22/previsao-churn-clientes-operadora.git
cd previsao-churn-clientes-operadora
