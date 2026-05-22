# 🛡️ Sistema de Machine Learning — Detecção de Fraudes em Cartão de Crédito

> Trabalho da Avaliação N1 — BSI / BCC
> Entrega: 22/05/2026

Projeto de Machine Learning supervisionado para identificar transações fraudulentas em cartão de crédito a partir de características das operações, lidando com forte desbalanceamento de classes.

---

## 📂 Conteúdo do repositório

| Arquivo | Descrição |
|---|---|
| `Deteccao_Fraudes_N1.ipynb` | Notebook principal com todos os 5 artefatos |
| `integrantes.txt` | Nome e RA de todos os integrantes do grupo |
| `README.md` | Este arquivo |

## 🚀 Como executar

### Opção 1 — Google Colab (recomendado)
1. Faça upload do arquivo `Deteccao_Fraudes_N1.ipynb` em [colab.research.google.com](https://colab.research.google.com)
2. Menu **Ambiente de execução → Executar tudo**
3. As bibliotecas usadas (pandas, numpy, scikit-learn, matplotlib, seaborn) já vêm pré-instaladas no Colab.

### Opção 2 — Localmente
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Deteccao_Fraudes_N1.ipynb
```

## 🎯 Artefatos entregues

| # | Artefato | Pontuação |
|---|---|---|
| 1 | Coleta e Limpeza de Dados | 10 pts |
| 2 | Desenvolvimento do Modelo de ML | 10 pts |
| 3 | Avaliação e Aprimoramento do Modelo | 10 pts |
| 4 | Visualização dos Resultados | 10 pts |
| 5 | Apresentação Final e Relatório | 10 pts |
| | **TOTAL** | **50 pts** |

## Algoritmos utilizados

- **Logistic Regression** — baseline para classificação binária
- **Random Forest** — modelo principal, com aprimoramento via regularização
- **K-Nearest Neighbors (KNN)** — comparação

## Principais resultados

- Dataset com 10.000 transações sintéticas (~5% de fraudes)
- Validação cruzada estratificada (5 folds) com F1-Score
- Random Forest aprimorado (`max_depth=10`) reduziu overfitting
- AUC-ROC acima de 0.95 no melhor modelo

## Bibliotecas

- `pandas`, `numpy` — manipulação de dados
- `scikit-learn` — modelos e métricas
- `matplotlib`, `seaborn` — visualizações

---

🎓 *Projeto desenvolvido como parte da avaliação N1 — 
