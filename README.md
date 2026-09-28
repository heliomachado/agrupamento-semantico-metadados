# Agrupamento Semântico e Detecção de Redundância em Metadados Corporativos

Este repositório contém o código-fonte desenvolvido para um estudo de
agrupamento semântico e detecção de potenciais redundâncias em metadados
heterogêneos de bancos de dados relacionais.

## Objetivo

Investigar a utilização de técnicas de mineração de dados e representação
semântica para identificar e agrupar estruturas de dados semanticamente
relacionadas em dicionários de dados corporativos.

## Metodologia

O trabalho utiliza Design Science Research (DSR) como metodologia científica
e CRISP-DM para condução do processo de mineração de dados.

## Pipeline

**Metadados → Preparação → BERTimbau → Embeddings (768D) → UMAP (5D) → HDBSCAN → Agrupamentos**

Também são utilizados experimentos baseline baseados em TF-IDF para
comparação dos resultados.

## Tecnologias

- Python
- BERTimbau
- SentenceTransformers
- UMAP
- HDBSCAN
- scikit-learn
- MySQL

## Dados

Os dados utilizados no estudo são metadados institucionais e não são
disponibilizados neste repositório por razões de segurança e
confidencialidade.

O repositório disponibiliza o código-fonte do pipeline. Dados sintéticos
poderão ser utilizados para demonstrar sua execução sem expor informações
institucionais.

## Estrutura do projeto

O código está organizado de acordo com as etapas do CRISP-DM:

- Fase 1 — Entendimento do Negócio
- Fase 2 — Entendimento dos Dados
- Fase 3 — Preparação dos Dados
- Fase 4 — Modelagem
- Fase 5 — Avaliação

A Fase 6 — Implantação representa a etapa subsequente do CRISP-DM e não
integra o escopo experimental apresentado neste repositório.

## Autor

Hélio Ramos Machado

Programa de Pós-Graduação em Computação Aplicada — PPCA  
Universidade de Brasília — UnB
