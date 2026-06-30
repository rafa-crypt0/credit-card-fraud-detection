# 💳 Detecção de Fraudes em Transações com Machine Learning

Projeto desenvolvido para estudar técnicas de Machine Learning aplicadas à detecção de fraudes em transações financeiras utilizando Python.

---

## 📌 Objetivo

Construir e comparar diferentes modelos de classificação capazes de identificar transações fraudulentas em um conjunto de dados altamente desbalanceado.

---

## 📊 Base de Dados

Foi utilizado o conjunto de dados disponibilizado pelo TensorFlow:

https://storage.googleapis.com/download.tensorflow.org/data/creditcard.csv

Características do dataset:

- 284.807 transações
- 31 variáveis
- Apenas 0,17% das transações são fraudes
- Variáveis V1 até V28 foram transformadas utilizando PCA para preservar a privacidade dos clientes.

---

## 🛠 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- XGBoost
- SHAP
- Imbalanced-learn (SMOTE)

---

## 📚 Etapas do Projeto

- Carregamento da base de dados
- Análise exploratória
- Verificação do desbalanceamento das classes
- Feature Engineering
  - Transformação logarítmica
  - Padronização dos dados
- Separação entre treino e teste
- Treinamento dos modelos
  - Logistic Regression
  - Random Forest
  - XGBoost
- Balanceamento dos dados
  - Undersampling
  - SMOTE
- Avaliação utilizando:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Curva ROC
  - Curva Precision-Recall
- Ajuste de hiperparâmetros com GridSearchCV
- Explicabilidade do modelo utilizando SHAP

---

## 📈 Resultados

O modelo XGBoost apresentou o melhor desempenho entre os modelos avaliados.

Exemplo de métricas obtidas:

| Métrica | Valor |
|----------|-------|
| Precision | 0.93 |
| Recall | 0.78 |
| F1-Score | 0.85 |

---

## 📂 Estrutura do Projeto

```
credit-card-fraud-detection/
│
├── credit-card-fraud-detection.ipynb
├── README.md
```

---

## 🚀 Como executar

1. Clone o repositório

```bash
git clone https://github.com/rafa-crypt0/credit-card-fraud-detection.git
```

2. Instale as dependências

```bash
pip install pandas numpy scikit-learn matplotlib xgboost shap imbalanced-learn
```

3. Abra o notebook

```bash
jupyter notebook
```

ou utilize o Google Colab.

---

## 📖 Aprendizados

Durante este projeto foram estudados conceitos como:

- Classificação supervisionada
- Desbalanceamento de classes
- Engenharia de atributos (Feature Engineering)
- Avaliação de modelos
- Random Forest
- XGBoost
- SHAP
- Ajuste de hiperparâmetros

---

## 👨‍💻 Autor

**Rafael Andrade Paiva**

GitHub:
https://github.com/rafa-crypt0
