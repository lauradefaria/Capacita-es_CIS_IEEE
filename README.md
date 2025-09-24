# Módulo (I): Estrutura de Dados, Pré Processamento e Machine Learning

Neste módulo, iremos explorar um conjunto abrangente de tópicos fundamentais para a ciência de dados e aprendizado de máquina utilizando a linguagem de programação Python. O conteúdo está estruturado para fornecer uma base sólida em estruturas de dados, bibliotecas essenciais de Python, técnicas de pré-processamento de dados e algoritmos de aprendizado supervisionado e não supervisionado. </br>

---

## Material de Apoio

Para auxilio com as questões, disponibilizamos o livro *Python para Estatísticos*, do professor Telmo de Menezes e Silva Filho, do Departamento de Estatística da Universidade Federal da Paraíba (UFPB):

[**Python para Estatísticos**](https://tmfilho.github.io/pyestbook)

Conteúdo de introdução para Python, realizado pela TAIL:

[**Introdução a python**](https://github.com/TailUFPB/CursoPyBasico/tree/main)

Link para bibliotecas essênciais para desenvolver os problemas abaixo:

[**Bibliotecas essenciais**](https://github.com/carlosfab/curso_data_science_na_pratica) </br>
[**Biblioteca Requests**](https://github.com/psf/requests)

Slides da disciplina de Introdução a Inteligência Artificial - Thaís Gaudêncio:  
  
[**Slides**](https://sites.google.com/site/gaudenciothaisia/home/aulas)

## Tabela de Conteúdos
- [Estrutura de Dados](#estrutura-de-dados)
- [Manipulando Bibliotecas](#manipulando-bibliotecas)
- [Acidentes Aereos](#acidentes-aereos)
- [Utilizando API](#utilizando-api)
- [Spotify Tracks Genre](#spotify-tracks-genre)

# 1.1 Estrutura de Dados e Manipulação de Bibliotecas

Neste notebook, começaremos com uma introdução às estruturas de dados em Python, abordando listas, tuplas, conjuntos, dicionários, e estruturas mais avançadas como pilhas, filas, árvores e grafos. Além disso, aprenderemos a utilizar bibliotecas essenciais para a ciência de dados: Pandas para manipulação de dados tabulares, Matplotlib para visualização de dados, NumPy para computação numérica eficiente e Scikit-learn para implementação de algoritmos de aprendizado de máquina. Essas ferramentas permitirão que você lide com dados de forma eficaz e aplique técnicas avançadas em seus projetos.

---

## Estrutura de Dados 

Começaremos com uma introdução às estruturas de dados em Python, fundamentais para qualquer projeto de ciência de dados. Abordaremos:

- Listas, tuplas, conjuntos e dicionários: conceitos, manipulação e uso em diversos contextos.
- Estruturas de dados: pilhas, filas, árvores e grafos, com foco em suas implementações e aplicações práticas.

## Manipulando Bibliotecas

Python é uma linguagem extremamente importante para a ciência de dados, em grande parte devido às suas bibliotecas. Neste módulo, aprenderemos a utilizar:

- Pandas: para manipulação e análise de dados tabulares.
- Matplotlib: para visualização de dados.
- NumPy: para computação numérica eficiente.
- Scikit-learn: para implementação de algoritmos de aprendizado de máquina.

# 1.2 Pré Processamento e Análise Exploratória de Dados

Este repositório foi desenvolvido com o objetivo principal de auxiliar no nivelamento dos membros existentes na divisão de Inteligência Computacional do Capítulo CS/CIS do Ramo Estudantil IEEE da Universidade Federal da Paraíba (UFPB). Nosso objetivo é proporcionar uma base sólida em análise de dados e aprendizado de máquina, essenciais para compreender e enfrentar os desafios do mundo contemporâneo.

---

## Acidentes Aereos

Utiliza-se dados abertos disponibilizados pela CENIPA - Centro de Investigação e Prevenção de Acidentes aeronáuticos. Tais arquivos conterão informações sobre ocorrências envolvendo aeronaves. Você pode acessar dados mais atualizados visitando <a href='http://dados.gov.br/dataset/ocorrencias-aeronauticas-da-aviacao-civil-brasileira'>a página oficial de Dados Abertos Brasileiros</a>, mas, caso deseje, poderá acessar o arquivo raw através do [link](https://raw.githubusercontent.com/carlosfab/dsnp2/master/datasets/ocorrencias_aviacao.csv).

# 1.3 Aprendizagem de Máquina e Manuseio de API

Neste notebook, exploraremos algoritmos de aprendizado supervisionado e não supervisionado essenciais para a ciência de dados. No aprendizado supervisionado, abordaremos Árvores de Decisão, Floresta Aleatória e K-Nearest Neighbors para classificação e regressão. No aprendizado não supervisionado, estudaremos K-Means e Agrupamento Hierárquico para detecção de padrões em dados não rotulados.

Além disso, trabalharemos com a utilização de APIs, que são interfaces de programação de aplicações, para acessar e integrar dados de diversas fontes externas.

---

## Utilizando API

Realiza a ingestão de dados por meio de uma API utilizando Python, com foco na transparência e disponibilização de informações relacionadas aos agentes públicos, utilizando a API pública da Câmara de Deputados como exemplo. O processo prático envolve a compreensão da estrutura dos dados, a utilização de Python para realizar requisições, o tratamento dos dados obtidos e a organização em uma estrutura para análise posterior.

A API pode ser acessada pelo [link](https://dadosabertos.camara.leg.br/api/v2/deputados). Para mais informações, pode ser visto os endpoints através da página de [Dados Abertos](https://dadosabertos.camara.leg.br/swagger/api.html).

## Spotify Tracks Genre

Este conjunto de dados fornece informações abrangentes sobre faixas do Spotify, abrangendo uma coleção diversificada de 125 gêneros. Ele foi compilado e limpo usando a API da Web do Spotify e Python. O conjunto de dados é composto por várias colunas, cada uma representando características de áudio distintas associadas a faixas individuais.

Todos os dados utilizados neste projeto foram baixados do repositório <a href="https://www.kaggle.com/datasets/thedevastator/spotify-tracks-genre-dataset/data">Spotify Tracks Genre</a>.
