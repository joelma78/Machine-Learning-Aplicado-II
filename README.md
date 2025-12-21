# **Modelos Preditivos para Adesão a Campanhas Bancárias: Uma Análise Baseada em Aprendizado de Máquina**

**Autores:** Antônio Cordeiro, Joelma Printes, Leticia Natividade, Luciano Carvalho  
**Instituição:** Universidade do Estado do Amazonas - UEA  
**Local:** Manaus – AM – Brasil  
**Orientação:** Prof. Dr. Juan G. Colonna

**Dataset:**(https://archive.ics.uci.edu/datasets/?search=bank+marketing)

- Bibliotecas: Scikit-learn, XGBoost, Gradio, Pandas

 
## 📋 **O que o projeto faz**
Este projeto implementa **modelos preditivos de aprendizado de máquina** para identificar clientes com maior probabilidade de aderir a campanhas de marketing bancário, especificamente para **depósitos a prazo**. O sistema analisa dados históricos de clientes e campanhas para prever comportamentos futuros de adesão.

**Principais funcionalidades:**
- Pré-processamento inteligente de dados bancários
- Implementação de múltiplos algoritmos (SVM, XGBoost, Regressão Logística, Naive Bayes)
- Balanceamento de classes com SMOTE
- Interface web interativa para predições em tempo real
- Análise exploratória completa dos fatores determinantes



## 📊 **Estrutura do projeto**
```
├── data/
│   └── bank-additional-full.csv        # Dataset original
│
├── notebooks/
│   └── ProjetoFinal_ML2.ipynb           # Notebook principal com toda a análise
│
├── models/
│   └── svm_model.pkl                   # Modelo final treinado (SVM)
│
├── app/
│   └── app_gradio.py                   # Aplicação interativa com Gradio
│
├── requirements.txt                    # Dependências do projeto
│
├── README.md                           # Documentação do projeto




⭐ **Se este projeto te ajudou, deixe uma estrela no GitHub!**
