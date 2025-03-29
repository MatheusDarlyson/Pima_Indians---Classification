# Detecção de Diabetes com CRISP-DM

Este repositório contém um projeto de aprendizado de máquina aplicado à classificação de diabetes utilizando o **Pima Indians Diabetes Dataset**. O desenvolvimento do projeto seguiu a metodologia **CRISP-DM (Cross-Industry Standard Process for Data Mining)**, garantindo um fluxo estruturado e bem definido para o desenvolvimento do modelo.

---

## Metodologia CRISP-DM

### Compreensão do Negócio

- **Definição do problema**: Predição da presença de diabetes em pacientes com base em variáveis clínicas.
- **Identificação de métricas de sucesso**: Precisão, recall, F1-score e matriz de confusão.

---

### Compreensão dos Dados

- Exploração do dataset **Pima Indians Diabetes Dataset**.
- Análise descritiva das variáveis.
- Identificação de inconsistências e valores ausentes.

---

### Preparação dos Dados

- Tratamento de valores nulos.
- Normalização e padronização de atributos.
- Divisão do conjunto de dados em treino e teste.

---

### Modelagem

- Definição do problema como **classificação binária**.
- Treinamento de modelos de classificação:
  - Logistic Regression
  - Random Forest
  - SVM

---

### Avaliação

- **Métricas de desempenho**:
  - Acurácia
  - Precision
  - Recall
  - F1-score
- Interpretação da matriz de confusão.
- Comparativo entre diferentes modelos.

---

### Implantação e Apresentação dos Resultados

- Visualização de resultados através de gráficos.
- Relatório com principais achados.
- Sugestões para melhorias futuras.

---

## Dataset

O **Pima Indians Diabetes Dataset** contém dados médicos de pacientes do povo Pima, incluindo informações como:

- Número de gestações
- Níveis de glicose no sangue
- Pressão arterial
- Espessura da pele do tríceps
- Insulina
- Índice de massa corporal (IMC)
- Histórico de diabetes na família
- Idade
- Diagnóstico de diabetes (`0 = não`, `1 = sim`)

---

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas**:
  - Pandas
  - NumPy
  - Scikit-Learn
  - Matplotlib
  - Seaborn
- **Ambiente**:
  - Jupyter Notebook / Google Colab
