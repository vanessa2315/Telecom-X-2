# Telecom X -- Parte 2: Prevendo Evasão de Clientes (Churn)

##  História do Desafio

Após o sucesso da análise exploratória na Parte 1, fui promovida e convidada a integrar a equipe de Machine Learning da Telecom X!
Nesta nova fase, o objetivo é construir modelos preditivos capazes de antecipar o risco de evasão de clientes, apoiando decisões estratégicas da empresa.

---

##  Missão

Desenvolver um pipeline robusto de machine learning para prever quais clientes têm maior chance de cancelar seus serviços,
utilizando técnicas de pré-processamento, modelagem e avaliação.

---

##  Objetivos do Projeto

- Preparar os dados para modelagem (tratamento, codificação, normalização).
- Realizar análise de correlação e seleção de variáveis.
- Treinar dois ou mais modelos de classificação.
- Avaliar o desempenho dos modelos com métricas apropriadas.
- Interpretar os resultados e identificar as variáveis mais relevantes.
- Criar uma conclusão estratégica com recomendações de retenção.

---

##  Tecnologias Utilizadas

- Python 3.x
- Google Colab
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

---

##  Etapas do Projeto

1.  **Carregamento e Limpeza dos Dados:**
    - Utilização do arquivo CSV tratado na Parte 1.
    - Remoção de colunas irrelevantes (ex: ID do cliente).

2.  **Pré-processamento e Análise Exploratória:**
    - **Codificação:** Aplicação de *One-Hot Encoding* para transformar variáveis categóricas em numéricas.
    - **Balanceamento:** Verificação da proporção de churn e aplicação de técnicas como SMOTE, se necessário.
    - **Normalização:** Padronização dos dados para modelos sensíveis à escala (ex: Regressão Logística).
    - **Correlação:** Visualização da matriz de correlação para identificar variáveis com maior impacto na evasão.

3.  **Modelagem Preditiva:**
    - **Divisão dos Dados:** Separação do dataset em conjuntos de treino (80%) e teste (20%).
    - **Treinamento:** Construção de pelo menos dois modelos distintos.
        - **Modelo 1 (com normalização):** Regressão Logística.
        - **Modelo 2 (sem normalização):** Random Forest.

4.  **Avaliação e Interpretação:**
    - **Métricas:** Análise de Acurácia, Precisão, Recall, F1-Score e Matriz de Confusão.
    - **Análise Crítica:** Comparação do desempenho dos modelos e verificação de *overfitting* ou *underfitting*.
    - **Importância das Variáveis:** Extração dos *features* mais relevantes de cada modelo para entender os principais fatores de risco.

---
