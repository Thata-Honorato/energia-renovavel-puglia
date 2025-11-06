# 🌞 Análise de Dados sobre Energia Renovável na Região da Puglia (Itália)

## 🧭 Visão Geral

Este projeto tem como objetivo explorar e analisar os **dados de solicitações de conexão à rede elétrica** para **instalações de fontes renováveis** na região da **Puglia (Itália)**.  
A proposta é identificar padrões, comparar a **rentabilidade e predominância** entre diferentes tipos de energia — como eólica, solar e biomassa — e compreender o **avanço da transição energética** na região.

---

## 🎯 Objetivos do Projeto

1. **Limpeza e padronização** dos dados brutos do portal de dados abertos da Puglia.  
2. **Análise exploratória** para identificar:
   - Distribuição das potências por tipo de energia.  
   - Crescimento de solicitações ao longo dos anos.  
   - Relação entre municípios e tipos de fonte energética predominantes.  
3. **Comparação de rentabilidade** e viabilidade entre as fontes renováveis.  
4. Criação de **visualizações interativas** e dashboards (futuro deploy no Streamlit).

---

## 🧰 Tecnologias Utilizadas

| Categoria | Ferramentas |
|------------|-------------|
| Linguagem principal | Python |
| Bibliotecas | pandas, numpy, matplotlib, seaborn, plotly |
| Ambiente de desenvolvimento | Jupyter Notebook |
| Fonte de dados | [Dati Puglia - Fonti Rinnovabili](https://dati.puglia.it/) |
| Versionamento | Git & GitHub |
| Visualização futura | Streamlit |

---

## 📂 Estrutura do Projeto

energia-renovavel-puglia/
│
├── dados/
│ ├── energia_renovavel_puglia.csv # arquivo original
│ ├── puglia_corrigido.csv # versão limpa e padronizada
│
├── notebooks/
│ ├── 01_limpeza_dados.ipynb # limpeza e padronização (fase atual)
│ ├── 02_exploracao_dados.ipynb # análise exploratória (próxima etapa)
│
├── README.md
└── requirements.txt


## 🚧 Status do Projeto

🔹 **Fase atual:** Bloco 1 – Limpeza e correção de estrutura do dataset  
🔹 **Próximos passos:**
- Padronizar nomes de colunas e tipos de dados.  
- Converter valores numéricos e datas.  
- Iniciar análise exploratória e comparativa entre fontes renováveis.
