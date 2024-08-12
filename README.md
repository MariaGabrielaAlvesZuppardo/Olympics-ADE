# Olympics

# Análise Exploratória dos Dados das Olimpíadas

Este projeto realiza uma Análise Exploratória dos Dados (EDA) sobre os Jogos Olímpicos utilizando dados históricos. O objetivo é entender melhor as características dos atletas, suas performances e as tendências ao longo dos anos.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

- **`data_analysis.py`**: Contém as classes `DataLoader` e `DataAnalyzer`. A classe `DataLoader` é responsável por carregar os dados dos arquivos CSV, enquanto a classe `DataAnalyzer` realiza a análise dos dados e gera visualizações.

- **`olympics_ade.ipynb`**: Notebook principal onde são realizadas as análises exploratórias e visualizações dos dados. Inclui também a execução de testes para validar o código.

## Arquivos CSV

O projeto utiliza os seguintes arquivos CSV:

- **`Athlete_Bio.csv`**: Informações sobre os atletas (ID, nome, sexo, altura, peso, país, etc.).
- **`Olympic_Athlete_Event_Results.csv`**: Resultados dos eventos olímpicos para cada atleta.
- **`Olympic_Games_Medal_Tally.csv`**: Contagem de medalhas por país em cada edição dos Jogos Olímpicos.
- **`Olympics_Results.csv`**: Detalhes sobre os resultados dos eventos olímpicos.
- **`Olympics_Country.csv`**: Mapeamento de códigos NOC para países.
- **`Olympics_Games.csv`**: Informações sobre as edições dos Jogos Olímpicos.

## Instalação

Certifique-se de ter as seguintes bibliotecas instaladas:

```bash
pip install pandas matplotlib seaborn

## Uso

    Carregue os Dados: Utilize a classe DataLoader para carregar os arquivos CSV.

    Realize a Análise: Use a classe DataAnalyzer para realizar análises e gerar visualizações dos dados.

    Execute Testes: Teste a funcionalidade das classes e métodos diretamente no notebook.
