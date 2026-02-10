# Aprovação de Empréstimos com Machine Learning

## 📌 Contexto
Instituições financeiras enfrentam riscos relevantes ao conceder crédito.
Este projeto desenvolve um modelo de classificação para apoiar a decisão
de aprovação de empréstimos, com foco na redução do risco de inadimplência.

## 🎯 Objetivo
Prever a probabilidade de aprovação de empréstimos (`Loan_Status = 'Y'`),
priorizando a **Precisão da classe aprovada** por meio da otimização do
threshold de decisão.

## 🧠 Abordagem
- Análise Exploratória de Dados (EDA)
- Pré-processamento dos dados
- Treinamento de modelo de classificação
- Avaliação com métricas orientadas a risco
- Ajuste de threshold para minimizar falsos positivos

## 📊 Resultados
A otimização do threshold permitiu aumentar a precisão das aprovações,
reduzindo a concessão de crédito para clientes com maior risco de inadimplência.

## 🛠️ Tecnologias
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📁 Estrutura do Repositório
aprovacao-emprestimos-ml/
- Aprovacao_Emprestimos_Classificacao_Profissional.ipynb
- data/
  - emprestimo_dataset.csv
- README.md

## 📌 Observações
Este projeto demonstra a importância de alinhar métricas de Machine Learning
aos objetivos de negócio, especialmente em contextos de risco financeiro.
