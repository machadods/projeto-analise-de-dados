# Análise e Segmentação de Clientes com RFM

Este projeto realiza uma análise completa de dados transacionais de e-commerce, com foco em **entendimento do comportamento de clientes** e **segmentação estratégica** utilizando a técnica RFM (Recency, Frequency, Monetary) combinada com clustering.

O objetivo não é criar modelos preditivos, mas **gerar insights acionáveis** para apoiar decisões de marketing, vendas e retenção de clientes.

---

## Objetivo do Projeto


Identificar
- Quais cliente geram mais valor
- Quais possuem maior recorrência
- Quais estão inativos ou em risco de abandono

A partir disso segmentar os clientes em grupos comportamentais claros, permitindo **priorização estratégica e redução de desperdício**.

---

# Metodologia

O projeto foi estruturado em três etapas principais:

### Análise Descritica

- Exploração do dataset
-  Avaliação de volume de vendas, faturamento e distribuição geográfica
-  Identificação de padrões gerias e concetração de receita

### Visualização de Dados

- Gráficos de faturamento por produto e país
- Curva de Parto para clientes
- Comunicação clar dos princiáis insights

### Mineração de Dados

- Construção das métricas RFM por cliente
- Normalização dos dados
- Aplicação do algoritmo KMeans (k = 4)
- Interpretação dos clusters resultantes

---

## Resultados Principais

A segmentação identificou **quatro grupos distintos de clientes**.

- **Clientes VIP**: poucos clientes com altíssima recorrência e valor
- **Clientes de Crescimento**: bom potencial para upsell e fidelização
- **Clientes Regulares**: grande volume, baixo ticket médio
- **Clintes Inativos**: baixa recorrência e longo tempo sem compra

Os resultados demonstram **forte concentração de receita em uma parcela da base**, reforçãndo a importância de estrátegias de retenção direcionadas.

---

## Estrutura do Projeto
projeto-analise-de-dados
│   .gitignore
│
├───.ipynb_checkpoints
├───data
│       online_retail_II.xlsx
│
├───docs
└───notebooks
    │   Análise_Descritiva.ipynb
    │   Mineração.ipynb
    │   Visualização.ipynb
    │
    |      Análise_Descritiva-checkpoint.ipynb
    └───.ipynb_checkpoints
            Mineração-checkpoint.ipynb
            Visualização-checkpoint.ipynb


## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Conclusção

O projeto demonstra como **análise simples, bem estruturadas e orientadas à decisão** podem transformar dados brutos em informações estratégicas.
Mais do que complexidade técnica,o foco está em **entender o problema certo e aplica o mais adequado**

*Projeto desenvolvido para fins de estudo, portfólio e demonstração de competências em análise de dados.*       
