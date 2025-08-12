###Projeto de Análise de Dados Imobiliários – Rio de Janeiro


  Este repositório apresenta um projeto de Análise de Dados desenvolvido a partir de uma base de preços de aluguéis de imóveis no Rio de Janeiro.
  O objetivo foi dar suporte ao time de Machine Learning e Desenvolvimento de um site imobiliário, preparando e enriquecendo os dados para uso em modelos preditivos e exibição no front-end.

##Contexto do Projeto
  A empresa imobiliária disponibilizou:

  Uma base de dados com informações sobre imóveis e seus respectivos valores de aluguel.

  Um quadro no Trello contendo as demandas e tarefas a serem executadas ao longo do projeto.

  O fluxo de trabalho seguiu um pipeline organizado em etapas, desde a exploração inicial até a criação de novas features.

##Estrutura das Demandas
  As tarefas estavam divididas em dois tipos:

  Demandas de Machine Learning (ML) 

  Análise exploratória dos dados (EDA)

  Tratamento de valores nulos

  Remoção de registros inconsistentes

  Aplicação de filtros específicos

  Salvamento dos dados processados

  Demandas de Desenvolvimento (DEV) 

  Criação de colunas numéricas

  Criação de colunas categóricas

##Etapas do Projeto
  Importação e exploração inicial da base

  Leitura do dataset utilizando Pandas

  Análise das dimensões, tipos de dados e amostras

  Análise Exploratória de Dados (EDA)

  Cálculo da média de preço por tipo de imóvel

  Percentual de distribuição dos tipos de imóvel

  Métodos utilizados: groupby(), value_counts(), unique(), query()

  Tratamento de Dados

  Preenchimento e remoção de valores nulos (isnull(), fillna(), drop())

  Exclusão de registros inconsistentes

  Aplicação de filtros para extração de dados específicos

  Feature Engineering

  Criação de duas colunas numéricas e duas categóricas
  
  Uso do método apply() e funções lambda para transformação de dados

## Tecnologias Utilizadas
  Python 3
  
  Pandas
  
  Jupyter Notebook
  
  Trello (gestão de tarefas)

## Principais Aprendizados
  Técnicas de limpeza e transformação de dados
  
  Aplicação de funções agregadoras e filtros avançados com Pandas
  
  Criação de novas features para enriquecer o dataset
  
  Organização de um fluxo de trabalho seguindo demandas de diferentes times (ML e DEV)

