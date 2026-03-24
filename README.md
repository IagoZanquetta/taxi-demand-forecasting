# taxi-demand-forecasting
Projeto de machine learning para prever a demanda de corridas de táxi e apoiar o planejamento operacional em horários de pico.

## Visão Geral

Este projeto tem como objetivo prever a quantidade de corridas de táxi em períodos futuros com base em dados históricos. A proposta é apoiar decisões operacionais, permitindo que a empresa antecipe picos de demanda e organize melhor a disponibilidade de motoristas.

A análise utiliza técnicas de preparação de séries temporais e modelos de machine learning para estimar o volume de pedidos em janelas futuras, com foco em qualidade preditiva e aplicabilidade prática.

## Problema de Negócio

Empresas de transporte precisam antecipar momentos de alta demanda para melhorar a alocação de recursos e reduzir tempo de espera dos clientes. Neste projeto, a meta é construir um modelo capaz de prever a demanda de corridas de táxi em um horizonte de curto prazo, ajudando no planejamento operacional.

## Conjunto de Dados

O conjunto de dados contém registros históricos de pedidos de táxi ao longo do tempo, permitindo analisar o comportamento da demanda e construir previsões baseadas em padrões temporais.

Dependendo da versão do projeto, os dados podem incluir informações como:

- data e hora
- quantidade de pedidos
- série temporal agregada por intervalo de tempo

Arquivo utilizado no projeto:

- `taxi.csv`

## Objetivos da Análise

Este projeto busca responder perguntas como:

- É possível prever a demanda de corridas de táxi com boa precisão?
- Quais padrões temporais influenciam o comportamento da série?
- Qual modelo apresenta melhor desempenho para previsão de curto prazo?
- Como as previsões podem apoiar o planejamento operacional em horários de pico?

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. carregamento e inspeção inicial dos dados
2. preparação e reamostragem da série temporal
3. criação de atributos temporais e defasagens
4. divisão entre treino e teste respeitando a ordem temporal
5. treinamento de modelos preditivos
6. avaliação com métricas apropriadas
7. comparação de resultados
8. conclusões de negócio

## Ferramentas e Bibliotecas

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Estrutura do Repositório

```text
taxi-demand-forecasting/
├── .gitignore
├── README.md
├── requirements.txt
├── taxi_demand_forecasting.ipynb
└── taxi.csv
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/taxi-demand-forecasting.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd taxi-demand-forecasting
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o arquivo `taxi_demand_forecasting.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.

5. Execute as células em ordem.

## Principais Pontos Analisados

Entre os principais focos do projeto, estão:

* comportamento temporal da demanda
* criação de variáveis para previsão
* comparação entre modelos de regressão
* avaliação de desempenho preditivo
* análise de aplicabilidade operacional
* recomendação de modelo final

## Resultados

O notebook inclui:

* preparação da série temporal
* engenharia de atributos
* treinamento e avaliação de modelos
* comparação de desempenho
* seleção do modelo final
* conclusões com foco em negócio

## Conclusão

Este projeto demonstra como técnicas de machine learning podem ser aplicadas à previsão de demanda em séries temporais para apoiar decisões operacionais. Ao antecipar padrões de pedidos de táxi, a análise contribui para melhorar planejamento, disponibilidade de recursos e eficiência do serviço.

## Autor

**Iago Zanquetta**
