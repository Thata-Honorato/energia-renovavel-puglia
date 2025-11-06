# 🌞 Análise de Dados sobre Energia Renovável na Região da Puglia (Itália)

## 🧭 Visão Geral

O projeto busca compreender como as diferentes fontes de energia renovável evoluíram na região da Puglia, analisando o volume de instalações, seus padrões de crescimento e a **rentabilidade** entre os distintos tipos de energia. Além disso, investiga os impactos econômicos e ambientais associados, com base em dados públicos, para responder a subquestões sobre **eficiência, distribuição territorial e sustentabilidade.**

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

## 🔍 Subquestões de Pesquisa

|*Para atingir o objetivo central, o estudo explora as seguintes subquestões analíticas:*|
|-

  🔹 1. Impactos ambientais 🌿

Quais tipos de energia apresentam maior potencial de redução de emissões?

Há uma correlação entre o crescimento das instalações renováveis e a diminuição de dependência de combustíveis fósseis?

Quais municípios estão liderando a transição energética e quais ainda têm baixa adesão?



  🔹 2. Impactos econômicos 📈

Como as diferentes fontes de energia se comparam em termos de potência instalada por investimento (eficiência econômica)?

Existe um retorno mais rápido para determinados tipos de energia (por exemplo, solar vs eólica)?

Municípios com maior produção renovável têm atraído mais investimento público/privado?



  🔹 3. Aspectos sociais e territoriais 🏞️

A expansão das fontes renováveis está distribuída de forma equilibrada ou concentrada em poucos municípios?

Existem áreas sub-representadas que poderiam receber mais incentivo?

Como o acesso à energia limpa pode impactar comunidades locais (empregos, infraestrutura, etc.)?



  🔹 4. Eficiência e tendência temporal 📉

Qual é o crescimento anual das instalações de energia renovável na Puglia?

Há tendências de substituição (ex: menos biomassa, mais solar)?

Existe sazonalidade nas solicitações de conexão?

-----

## 💡 Justificativa

Compreender o panorama das energias renováveis na Puglia contribui para avaliar a eficiência das políticas energéticas, a sustentabilidade regional e o equilíbrio entre crescimento econômico e preservação ambiental.
Além disso, o estudo oferece insumos estratégicos para futuras análises comparativas entre regiões italianas ou europeias.

------

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

