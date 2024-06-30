# Descrição
Este projeto é um software desenvolvido em Python e organizado na plataforma Jupyter Notebook com o objetivo de coletar informações de tarefas do software de apoio à gestão de projetos Jira. O sistema extrai dados sobre responsáveis, tempo estimado e tempo gasto em cada tarefa. Além disso, analisa os textos descritos nas descrições e comentários das tarefas para classificar os sentimentos presentes no conteúdo textual.

## Funcionalidades

### Coleta de Dados:
Conexão com a API do Jira para coletar informações sobre tarefas.
Extração de dados como responsáveis, tempo estimado e tempo gasto em cada tarefa.

### Análise de Sentimentos:
Análise de textos presentes nas descrições e comentários das tarefas.
Classificação dos sentimentos expressos nos textos (Happy, Angry, Surprise, Sad, Fear) através da utilização da biblioteca text2emotion.
