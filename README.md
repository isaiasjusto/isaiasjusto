# Olá, eu sou Isaias Justo 👋

### Data Scientist | Machine Learning, Analytics & Data Engineering

Transformo dados em decisões, produtos analíticos e sistemas de Machine Learning rastreáveis.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Isaias_Justo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/isaias-justo-a8b998185/)
[![Portfólio](https://img.shields.io/badge/Portfólio-isaiasjusto.github.io-0F766E?style=for-the-badge&logo=githubpages&logoColor=white)](https://isaiasjusto.github.io)
[![Email](https://img.shields.io/badge/Email-isaiasj2906%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:isaiasj2906@gmail.com)

---

## Sobre mim

Atuo profissionalmente com **dados, Business Intelligence e soluções analíticas**, conectando necessidades de negócio a produtos de dados claros, confiáveis e acionáveis.

Meus projetos exploram o ciclo completo: ingestão e transformação de dados, análise exploratória, modelagem, avaliação, MLOps, explicabilidade, APIs e aplicações analíticas.

- Ciência de Dados e Machine Learning aplicados a churn, crédito, fraude e NLP
- Analytics Engineering com SQL, PostgreSQL e dbt
- MLOps com MLflow, MinIO, Docker e FastAPI
- Explicabilidade com SHAP e governança de IA
- Analytics e BI com Power BI, Microsoft Fabric e PySpark
- Aplicações de dados com Streamlit
- IA generativa local com Ollama, Llama e contratos Pydantic

---

## Projeto principal

### [FinPulse AI](https://github.com/isaiasjusto/finpulse-ai)

Plataforma end-to-end para **previsão de churn bancário, explicabilidade e retenção governada**.

```text
MinIO → PostgreSQL → dbt → CatBoost → MLflow
      → Batch Scoring → FastAPI → SHAP
      → Streamlit → Ollama / Llama → Revisão humana
```

Principais resultados:

- **10.127 clientes** processados e pontuados
- benchmark de dez algoritmos e **CatBoost champion v3**
- **ROC AUC 0,9934** e **F1-score 0,9206** no teste reservado
- previsões persistidas no PostgreSQL e snapshot Parquet no MinIO
- explicabilidade global e individual com SHAP
- API com FastAPI e dashboard multipágina em Streamlit
- Cliente 360 com recomendação de retenção gerada por IA local
- catálogo determinístico de ações e política obrigatória para casos prioritários
- bloqueio de atributos pessoais não acionáveis no contexto operacional
- validação por Pydantic e revisão humana obrigatória
- **37 testes automatizados** na suíte da API

Próxima evolução: Assistente FinPulse com chat governado, RAG para documentos controlados e fluxos autorizados via n8n.

---

## Outros projetos em destaque

| Projeto | O que foi construído | Tecnologias |
|---|---|---|
| [Modelo de Aprovação de Crédito](https://github.com/isaiasjusto/credit-approval-risk-model) | EDA estruturado, prevenção de leakage, benchmark de modelos e threshold orientado a custo. XGBoost com ROC AUC aproximado de 0,97. | Python, Pandas, Scikit-learn, XGBoost, LightGBM |
| [GamePulse AI](https://github.com/isaiasjusto/gamepulse-ai) | Classificação de avaliações de jogos em sete categorias com fine-tuning do BERTimbau. Acurácia de 91,67% no conjunto inicial de teste. | PyTorch, CUDA, Hugging Face, BERTimbau, Streamlit |
| [Portfólio de Dados](https://github.com/isaiasjusto/isaiasjusto.github.io) | Portfólio pessoal reunindo projetos de Data Science, BI e Machine Learning. | HTML, CSS, JavaScript, GitHub Pages |

---

## Stack técnica

### Dados e Analytics

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-742774?style=flat-square&logo=microsoft&logoColor=white)

### Machine Learning e IA

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black)
![XGBoost](https://img.shields.io/badge/XGBoost-EC4E20?style=flat-square&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-2563EB?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-111111?style=flat-square)

### Engenharia e entrega

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Em construção

Atualmente estou evoluindo o **FinPulse AI** para uma central conversacional governada, capaz de consultar clientes, carteira e políticas sem permitir que o LLM recalcule risco, invente evidências ou execute ações sem confirmação humana.

---

> Dados, modelos e IA só geram valor quando conseguem sustentar decisões compreensíveis, rastreáveis e responsáveis.
