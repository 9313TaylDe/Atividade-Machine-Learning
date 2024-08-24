# Classificação de expressões faciais

Este projeto utiliza técnicas de Visão Computacional e Redes Neurais Convolucionais (CNN) para classificar expressões faciais humanas, por meio da base de dados **Human Face Emotions** do Kaggle.
<div align="center">
    <img src="figs/dataset-cover.jpg" alt="Braço robótico didático" width="250" height="150">
    <br>
</div>

## Base de Dados

A base de dados [Human Face Emotions](https://www.kaggle.com/datasets/sanidhyak/human-face-emotions) contém três pastas: Feliz, Triste e Bravo. Cada pasta contém cerca de 100 imagens de cada expressão mencionada. Esta base de dados pode ser utilizada para vários propósitos, incluindo classificação usando Redes Neurais Convolucionais e Visão Computacional.

Para tanto, foi utilizado uma base de dados editada conforme a necessidade proposta vista ao longo do tempo.
 [Dataset](9313TaylDe/Atividade-Machine-Learning/src/data/link-base-dados.txt)


## Etapas do Projeto

- [X] **Coleta e Análise Exploratória dos Dados**
   - Coleta dos dados da base Human Face Emotions.
   - Análise exploratória dos dados para entender a distribuição e características das imagens.

- [X] **Pré-processamento dos Dados**
   - Limpeza e normalização das imagens.
   - Divisão dos dados em conjuntos de treino, validação e teste.

- [X] **Desenvolvimento do Modelo**
   - Criação e treinamento de modelos utilizando Redes Neurais Convolucionais (CNN).
   - Avaliação dos modelos com métricas apropriadas.

- [X] **Validação e Teste do Modelo**
   - Validação cruzada para garantir a robustez do modelo.
   - Teste final com o conjunto de dados de teste.

- [X] **Implementação e Predição**
   - Implementação do modelo final.
   - Criação de um script para predições em novas imagens.

- [X] **Documentação e Relatórios**
   - Documentação do código e das metodologias utilizadas.
   - Criação de relatórios e visualizações dos resultados.
