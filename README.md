# projeto-inadimplencia
Projeto de Ciência de Dados completo: análise e previsão de inadimplência de clientes.

# Projeto: Previsão de Inadimplência

Este projeto tem como objetivo construir uma solução completa de análise e previsão de inadimplência de clientes, utilizando técnicas de ciência de dados e machine learning.

## Objetivos

- Análise exploratória de dados (EDA)
- Engenharia de variáveis
- Construção de modelos de machine learning
- Avaliação e comparação de desempenho dos modelos
- Deploy local e visualizações

## Estrutura do Projeto

projeto-inadimplencia/
│
├── data/ → Arquivos CSV e dados brutos
├── notebooks/ → Jupyter Notebooks com análises
├── scripts/ → Scripts Python reutilizáveis
├── models/ → Modelos treinados
├── figures/ → Gráficos salvos
├── venv/ → Ambiente virtual (IGNORADO pelo Git)
├── requirements.txt → Bibliotecas usadas
├── README.md → Explicação do projeto
├── .gitignore → Ignora venv, .env, etc.



## Dados

Os dados simulados incluem:

- ID do cliente
- Idade
- Renda mensal
- Valor total da dívida
- Número de parcelas vencidas
- Score de crédito
- Indicador de inadimplência (`inadimplente`: 0 ou 1)

## Requisitos

Crie um ambiente virtual e instale as dependências:

```bash
python -m venv venv
venv\Scripts\activate 
pip install -r requirements.txt 
```

## Como usar
1. Execute as análises no Jupyter Notebook da pasta notebooks/.

2. Use os scripts da pasta scripts/ para treinar modelos ou transformar dados.

3. Visualize os gráficos salvos em figures/.

## Autor
Projeto feito por Adria Barreto. Inspirado por problemas reais de previsão de crédito.


---

### 2.Arquivo CSV de dados simulados

Criei um arquivo chamado `clientes_inadimplencia.csv` com dados sintéticos para 100 clientes. Aqui está um trecho dos dados:

| id_cliente | idade | renda_mensal | valor_divida | parcelas_vencidas | score_credito | inadimplente |
|------------|-------|--------------|--------------|-------------------|---------------|--------------|
| 1          | 34    | 3200.00      | 1500.00      | 2                 | 620           | 1            |
| 2          | 45    | 5500.00      | 0.00         | 0                 | 780           | 0            |
| 3          | 29    | 4100.00      | 900.00       | 1                 | 660           | 0            |
| ...        | ...   | ...          | ...          | ...               | ...           | ...          |


