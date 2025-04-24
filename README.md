# Classificação de Dados de Seguro com Gaussian Naive Bayes 🧠📊

Este projeto consiste na construção de um modelo de classificação utilizando o algoritmo Gaussian Naive Bayes (Scikit-learn) com uma base de dados de seguros. O objetivo é prever categorias ou comportamentos com base em atributos do cliente.

## 🔧 Tecnologias Utilizadas
- Python 3.x
- pandas
- numpy
- scikit-learn
- (Opcional) yellowbrick

## 📂 Funcionalidades do Projeto
- Leitura e limpeza de dados (`pandas`)
- Codificação de variáveis categóricas (`LabelEncoder`)
- Separação da base em treino/teste (`train_test_split`)
- Treinamento do modelo com `GaussianNB`
- Avaliação com métricas: Acurácia, Precisão, Recall, F1-score
- Relatório de classificação com `classification_report`

## 🚀 Como Executar
1. Clone o repositório:

        git clone https://github.com/seu-usuario/NaiveBayes_Insurance_Classifier.git
Instale as dependências:

       pip install -r requirements.txt
Execute o script principal:

       python naive_bayes_insurance.py
📈 Exemplo de saída:

    Acurácia: 0.82, Precisão: 0.81, Recall: 0.83, F1: 0.82
    Relatório de Classificação:
    [...]
  ## 📌 Objetivo de aprendizado
Este projeto visa aplicar conceitos de Machine Learning supervisionado e manipulação de dados com foco em classificação real.
