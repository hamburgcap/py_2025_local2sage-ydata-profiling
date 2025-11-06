# 📊 Local EDA & Data Profiling for ML (Local2Sage-YData)

| 🇧🇷 Português | 🇬🇧 English |
|---|---|
| Laboratório local de EDA com foco em **qualidade de dados**, usando `ydata-profiling` para gerar um relatório automático completo antes de migrar um pipeline para o AWS SageMaker. | Local-first EDA lab focused on **data quality** using `ydata-profiling` to generate a complete automated report before migrating a pipeline to AWS SageMaker. |

---

## 🚀 Objetivo / Purpose

| 🇧🇷 | 🇬🇧 |
|---|---|
| Avaliar rapidamente a qualidade dos dados (missing, outliers, tipos, cardinalidade) e detectar possíveis problemas **antes de custar dinheiro** em nuvem. | Quickly assess data quality (missing, outliers, types, cardinality) and detect issues **before burning cloud budget**. |

---

## 🧱 Arquitetura simples / Simple architecture

raw data → Jupyter EDA → ydata-profiling HTML report → (future) SageMaker

<img src="https://img.shields.io/badge/AWS-ready-orange" />
<img src="https://img.shields.io-badge/Data_Quality-✓-brightgreen" />

---

## 📂 Estrutura / Structure

py_2025_local2sage-ydata-profiling/
├─ notebooks/                # Notebook fonte da análise exploratória
│  └─ eda_parquet.ipynb
├─ reports/                  # Resultado gerado (HTML interativo)
│  └─ relatorio_ydata.html
└─ README.md                 # Este arquivo

✅ Sem dados sensíveis versionados  
✅ HTML é gerado automaticamente pelo notebook

---

## ▶️ Como rodar / How to run

| 🇧🇷 | 🇬🇧 |
|---|---|
| Abra o notebook e execute as células: | Open the notebook and run all cells: |
| `notebooks/eda_parquet.ipynb` | `notebooks/eda_parquet.ipynb` |

🎯 O relatório será salvo automaticamente em:

reports/relatorio_ydata.html

---

## 🎯 Próximos passos / Next steps

| 🇧🇷 | 🇬🇧 |
|---|---|
| - Pipeline de pré-processamento (limpeza, encoding, imputação) <br> - Exportar dataset pronto para experimento no SageMaker <br> - Métricas iniciais para baseline | - Preprocessing pipeline (cleaning, encoding, imputing) <br> - Export ready-to-train dataset for SageMaker <br> - Baseline metrics validation |

---

## 🧰 Tecnologias / Tech Stack

- Jupyter Notebook
- Python + Pandas
- **ydata-profiling** (ex-pandas-profiling)
- AWS-ready mindset ✅

---

## 📌 Portfolio Note

> Este projeto demonstra como **reduzir custo e tempo** ao validar dados **localmente** antes de mover para ML em produção.

> This project demonstrates how to **reduce cost and time** by validating data **locally** before moving to production ML.
