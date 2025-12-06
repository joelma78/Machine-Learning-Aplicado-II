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
bank-prediction/
├── src/                    # Código-fonte principal
│   ├── preprocessing.py    # Pré-processamento de dados
│   ├── models.py          # Implementação dos modelos
│   ├── evaluation.py      # Métricas e validação
│   └── predictor.py       # API de predição
├── notebooks/             # Análises exploratórias
│   ├── 01_eda.ipynb      # Análise exploratória
│   └── 02_modelos.ipynb  # Desenvolvimento de modelos
├── data/                  # Dados e processamentos
│   ├── raw/              # Dados originais
│   └── processed/        # Dados processados
├── models/               # Modelos treinados
│   └── best_model.pkl   # Modelo otimizado
├── app.py               # Interface Gradio
├── requirements.txt     # Dependências
├── config.yaml         # Configurações
└── README.md           # Esta documentação
```



⭐ **Se este projeto te ajudou, deixe uma estrela no GitHub!**
