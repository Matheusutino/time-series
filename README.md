# SCC5977 - Aprendizado de Máquina para Séries Temporais (2024)

Este repositório contém o código dos projetos 1 e 2 da disciplina **SCC5977 - Aprendizado de Máquina para Séries Temporais (2024)**, ministrada pelo professor **Dr. Diego Furtado Silva**. O objetivo desta disciplina é explorar técnicas de aprendizado de máquina aplicadas à análise de séries temporais.

## Autores

| Nome                                     | NUSP       |
|------------------------------------------|------------|
| Matheus Yasuo Ribeiro Utino              | 11233389   |
| João Gabriel Zanão Costa                | 11234266   |
| Ana Rita Marega Gonçalves                | 15746365   |

## Descrição do Projeto 1

Neste trabalho, o objetivo foi a detecção de arritmias cardíacas a partir de sinais de ECG, utilizando o _MIT-BIH Arrhythmia Database_. A tarefa envolveu o desenvolvimento e aplicação de técnicas de aprendizado de máquina para identificar padrões de arritmias, que são condições potencialmente perigosas para os pacientes.

A técnica principal utilizada foi o cálculo do _Matrix Profile_, que é uma estrutura de dados eficiente para analisar séries temporais, permitindo identificar padrões repetitivos (_motifs_), anomalias (_discords_) e subsequências discriminativas (_shapelets_). Esse método foi empregado para detectar anomalias nos sinais de ECG e para buscar padrões específicos de arritmias nas sequências temporais de dados.

A metodologia de detecção de anomalias envolveu o uso do MP para calcular as distâncias entre subsequências, estabelecendo um limiar para identificar os pontos anômalos. Para a busca de padrões, foi utilizada uma técnica de consulta (_query_) para comparar subsequências e encontrar padrões semelhantes na série temporal.

Essas abordagens foram fundamentais para a detecção de arritmias cardíacas, permitindo automatizar o pré diagnóstico de doenças cardíacas em contextos clínicos.


## Como Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Matheusutino/time-series.git

2. **Navegue até a pasta do trabalho desejado:**
   - Para o **Trabalho 1**, use:
     ```bash
     cd time-series/trabalho-1
     ```
   - Para o **Trabalho 2**, use:
     ```bash
     cd time-series/trabalho-2
     ```
3. **Instale as dependências:**
   ```bash
     pip install -r requirements.txt
4. **Execute o script main.ipynb**

