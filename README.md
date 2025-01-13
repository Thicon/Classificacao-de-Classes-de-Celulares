# **Projeto de Classificação - Classes de preços de celulares**

---------------------

## **1. Apresentação**

### **1.1. Possíveis problemas, questões e observações**
- A classificação pode ser útil em diferentes cenários, pois é criada uma "target" que difrrencia dados com base em características
- Neste cenário a classificação popde ser útil para:
  - Possíveis recomendações após uma segmentação de clientes (com base em interesses, cliques, preferências...)
  - Analisar as features mais influentes na classe-alvo (target).
  - Descobrir padrões ocultos nos dados e que influenciam de modo geral.
  - Automações em recomendações.


### **1.2. Contexto das pastas e arquivos do repositório**

- data
  - train.csv e test.csv: dados de treino e teste para o modelo
- images
  - Imagens geradas nas análises de EDA
- notebooks
  - Arquivos .ipynb (cadernos Jupyter), onde o projeto foi feito
- models
  - Pipeline com o pré-processamento e o modelo
- streamlit
  - Imagens relacionadas ao app streamlit
- gitignore
  - Arquivo que contém o que não deve ser versionado
- requirements
  - Todas as bibliotecas utilizadas no projeto, junto com suas versões

### **1.3. O que foi atualizado com relação ao projeto antigo?**

|                     Projeto anterior (1 ano atrás)                  |                                              Projeto atual                                      |
| --------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| Código não versionado com Git                                       |   Código versionado com o Git, permitindo voltar a estágios anteriores                          |
| Apenas um notebook para todas as etapas (EDA e Machine Learning     |   Pastas e arquivos organizados de acordo com sua finalidade                                    |
| Sem pipeline e exportação do modelo                                 |   Pipeline completo exportado com o joblib, para utilizar no Streamlit                          |
| Interação apenas do notebook                                        |   App Streamlit para inserir as features e prever a classe do preço                             |
| Sem a pasta "images" com os gráficos feitos                         |   Imagens dos gráficos disponibilizadas nas pastas "images" e "streamlit"                       |

### **1.4. Fonte das bases de dados**

link: https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification



