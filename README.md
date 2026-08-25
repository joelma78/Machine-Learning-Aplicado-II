# 📊 Modelos Preditivos para Adesão a Campanhas Bancárias

> **Projeto de Machine Learning aplicado à previsão de adesão de clientes a campanhas de marketing bancário.**

Este projeto desenvolve e compara **modelos de Aprendizado de Máquina** capazes de identificar clientes com maior probabilidade de aderir a uma campanha bancária para contratação de **depósitos a prazo**.

A solução envolve desde a **análise exploratória e preparação dos dados** até o treinamento, avaliação e disponibilização de um modelo preditivo por meio de uma **interface interativa com Gradio**.

---

## 🎯 Objetivo

Construir um modelo preditivo capaz de classificar clientes de acordo com a probabilidade de **aderirem ou não à campanha bancária**, utilizando informações relacionadas ao perfil do cliente e às características da campanha.

O projeto busca demonstrar, na prática, a aplicação de técnicas de **Ciência de Dados e Machine Learning** em um problema de classificação binária.

---

## 🔎 Sobre o projeto

O desenvolvimento contempla as principais etapas de um projeto de Machine Learning:

* 📥 Carregamento e exploração dos dados
* 🧹 Tratamento e preparação das variáveis
* 🔄 Transformação de variáveis categóricas
* ⚖️ Balanceamento das classes com **SMOTE**
* 📊 Análise exploratória dos dados
* 🤖 Treinamento de diferentes algoritmos
* 📈 Avaliação e comparação dos modelos
* 💾 Persistência do modelo treinado
* 🖥️ Desenvolvimento de uma interface interativa com **Gradio**

---

## 🤖 Modelos utilizados

Foram implementados e comparados diferentes algoritmos de classificação:

| Modelo               | Aplicação                             |
| -------------------- | ------------------------------------- |
| Logistic Regression  | Classificação e modelo de referência  |
| Gaussian Naive Bayes | Classificação probabilística          |
| SVM                  | Classificação com margem de separação |
| XGBoost              | Modelo baseado em árvores de decisão  |

Após a comparação dos resultados, o **SVM apresentou o melhor desempenho considerando a métrica F1-Score**, sendo selecionado como modelo final.

---

## ⚙️ Pipeline de Machine Learning

O fluxo do projeto pode ser representado da seguinte forma:

```text
Dados brutos
     ↓
Análise exploratória
     ↓
Tratamento dos dados
     ↓
Codificação das variáveis categóricas
     ↓
Separação entre X e y
     ↓
Train / Test Split
     ↓
Balanceamento com SMOTE
     ↓
Treinamento dos modelos
     ↓
Avaliação das métricas
     ↓
Comparação dos modelos
     ↓
Seleção do melhor modelo
     ↓
Modelo SVM
     ↓
Interface Gradio
```

---

## 📊 Dataset

O projeto utiliza o **Bank Marketing Dataset**, disponibilizado pelo **UCI Machine Learning Repository**.

O conjunto de dados contém informações relacionadas a clientes de uma instituição bancária e às campanhas de marketing realizadas.

🔗 **Fonte:**
[UCI Machine Learning Repository — Bank Marketing](https://archive.ics.uci.edu/datasets/?search=bank+marketing)

---

## 🧰 Tecnologias e bibliotecas

### Linguagem

* 🐍 Python

### Ciência de Dados

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn
* XGBoost
* Imbalanced-learn / SMOTE

### Aplicação

* Gradio

### Ambiente

* Google Colab
* Jupyter Notebook
* GitHub

---

## 📁 Estrutura do projeto

```text
previsao-adesao-campanha-bancaria/
│
├── data/
│   └── bank-additional-full.csv
│
├── notebooks/
│   └── ProjetoFinal_ML2.ipynb
│
├── models/
│   └── svm_model.pkl
│
├── app/
│   └── app_gradio.py
│
├── requirements.txt
│
└── README.md
```

### 📂 Descrição das pastas

**`data/`**
Contém o conjunto de dados utilizado no projeto.

**`notebooks/`**
Contém o notebook com as etapas de análise, preparação, treinamento e avaliação dos modelos.

**`models/`**
Armazena o modelo final treinado.

**`app/`**
Contém a aplicação desenvolvida com Gradio para realizar previsões.

**`requirements.txt`**
Lista as principais dependências necessárias para executar o projeto.

---

## 📈 Avaliação dos modelos

Para avaliar o desempenho dos algoritmos, foram utilizadas métricas adequadas para problemas de classificação, com destaque para:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Matriz de Confusão**

O **F1-Score** recebeu atenção especial devido ao possível desbalanceamento entre as classes, buscando equilibrar **Precisão** e **Recall**.

---

## 🖥️ Interface de predição

O modelo final foi integrado a uma aplicação desenvolvida com **Gradio**, permitindo que o usuário informe características de um cliente e obtenha uma previsão do modelo.

```text
Dados do cliente
      ↓
Interface Gradio
      ↓
Pipeline de Machine Learning
      ↓
Modelo SVM
      ↓
Predição
```

---

## 💡 Aplicação prática

Uma solução desse tipo pode auxiliar instituições financeiras na:

* identificação de clientes com maior propensão à adesão;
* segmentação de campanhas;
* priorização de contatos;
* análise do perfil dos clientes;
* tomada de decisões orientadas por dados.

> **Importante:** o modelo possui finalidade acadêmica e experimental e não deve ser utilizado isoladamente para decisões financeiras reais.

---

## 👥 Autores

**Antônio Cordeiro**
**Joelma Printes**
**Leticia Natividade**
**Luciano Carvalho**

### 🎓 Instituição

**Universidade do Estado do Amazonas — UEA**

📍 Manaus – AM – Brasil

### 👨‍🏫 Orientação

**Prof. Dr. Juan G. Colonna**

---

## 🚀 Competências demonstradas

Este projeto demonstra conhecimentos práticos em:

`Python` · `Data Science` · `Machine Learning` · `Classificação` · `EDA` · `Feature Engineering` · `SMOTE` · `Scikit-learn` · `XGBoost` · `SVM` · `Model Evaluation` · `Gradio`

---

## 📌 Projeto acadêmico

Projeto desenvolvido no contexto acadêmico da **Universidade do Estado do Amazonas (UEA)**, com aplicação prática de técnicas de **Ciência de Dados e Aprendizado de Máquina**.

---

⭐ **Se este projeto foi útil ou interessante, considere deixar uma estrela no repositório.**
