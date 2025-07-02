# Análise de Dados do Mercado Financeiro com Python e Power BI

Este projeto tem como objetivo realizar uma análise de dados do mercado financeiro, utilizando Python para a extração e tratamento dos dados, e Power BI para a visualização e criação de dashboards interativos. O projeto foi desenvolvido com base no curso "Python e Power BI: analisando dados do mercado financeiro" da Alura.

## Visão Geral

O projeto se concentra na extração de cotações de ativos financeiros utilizando a biblioteca `yfinance` do Python, no tratamento desses dados com `pandas` e na preparação para a importação e visualização no Power BI.

## Estrutura do Projeto

O projeto é composto pelas seguintes etapas principais:

1.  **Extração de Dados com Python:**
    *   Utilização da biblioteca `yfinance` para extrair dados históricos de cotações de uma carteira de ativos.
    *   Definição de um período específico para a extração dos dados (ex: 01/08/2022 a 01/08/2023).
    *   Transformação dos dados extraídos em um formato adequado para análise, utilizando a função `stack()` do pandas para reorganizar as colunas e resetando o índice para facilitar a manipulação dos dados.
    *   Limpeza e organização dos dados, removendo colunas desnecessárias e mantendo apenas as informações relevantes (Data, Open, High, Low, Close, Ativo).
2.  **Preparação dos Dados para o Power BI:**
    *   Verificação dos tipos de dados das colunas para garantir a compatibilidade com o Power BI.
    *   Exportação dos dados tratados para um formato adequado para importação no Power BI (ex: CSV).
3.  **Visualização e Análise no Power BI:**
    *   Importação dos dados no Power BI.
    *   Criação de dashboards interativos para visualizar as cotações dos ativos ao longo do tempo.
    *   Implementação de medidas e cálculos personalizados para análise dos dados.

## Requisitos

Para executar este projeto, você precisará ter as seguintes ferramentas e bibliotecas instaladas:

*   [Python](https://www.python.org/downloads/) (versão 3.6 ou superior)
*   [Power BI Desktop](https://powerbi.microsoft.com/pt-br/desktop/)
*   Bibliotecas Python:
    *   `yfinance`
    *   `pandas`

Você pode instalar as bibliotecas Python utilizando o pip:

```bash
pip install yfinance pandas