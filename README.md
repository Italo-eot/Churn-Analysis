# 📊 Análise de Churn

## 📌 Contexto
A análise de dados desempenha um papel fundamental na identificação de padrões de comportamento e na tomada de decisões estratégicas dentro das empresas.  
No contexto de negócios baseados em assinaturas (SaaS), compreender o comportamento dos clientes ao longo do tempo é essencial para manter uma base de usuários ativa e engajada.

Neste estudo, o objetivo foi **investigar os fatores associados ao aumento do churn** (cancelamento de contratos) utilizando **estatística descritiva**, **análises univariadas e multivariadas**, e explorando também **modelos de machine learning** para apoiar decisões.

---

## 🎯 Objetivos
- Identificar variáveis mais relacionadas ao churn.
- Avaliar comportamentos e padrões no perfil de clientes.
- Criar visualizações claras para comunicar insights.
- Utilizar técnicas preditivas para estimar risco de churn.

---

## 🛠️ Tecnologias utilizadas
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook**
- **Estatística descritiva e inferencial**
- **Machine Learning** (Modelos preditivos e métricas de avaliação)

---

## 🔍 Metodologia
1. **Análise Univariada**  
   - Distribuições de variáveis.
   - Taxa de churn por categoria.
   - Identificação de padrões individuais.

2. **Análise Multivariada**  
   - Correlações entre variáveis.
   - Relação conjunta de fatores que explicam o churn.
   - Testes estatísticos.

3. **Modelagem Preditiva** *(opcional)*  
   - Modelos supervisionados para prever churn.
   - Avaliação com métricas como AUC, precisão e recall.

---

## 📈 Principais Insights
- Alguns perfis de clientes apresentaram taxas de churn significativamente mais altas.
- Determinadas combinações de fatores (uso + perfil demográfico) aumentam a probabilidade de cancelamento.
- A análise multivariada revelou interações que não eram visíveis na análise univariada.

---

## 📂 Estrutura do repositório
```plaintext
├── Churn.ipynb          # Notebook com todas as análises
├── README.md            # Descrição do projeto
└── (sem dados)          # Base original não incluída


💡 Próximos Passos
Testar outros algoritmos de machine learning.

Implementar pipeline automatizado de previsão de churn.

Criar dashboard interativo (Streamlit/Power BI).