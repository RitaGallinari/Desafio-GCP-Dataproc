# Desafio-GCP-Dataproc

O desafio faz parte do curso na plataforma da Digital Innovation One:

Criando um ecossistema Hadoop totalmente gerenciado com o Google Cloud Platform

O desafio consistiu em um processamento de dados usando o Dataproc do GCP. Esse destino programado um livro informado a contagem das palavras de cada informar e muitas vezes aparece no mesmo 

## Etapas  do  Desafio
Criar um bucket no Cloud Storage 

Atualizar o arquivo contador.pycom o nome do Bucket criado nas linhas que contém {SEU_BUCKET}.

Fazer o upload dos arquivos contador.pye livro.txtpara o bucket criado (instruções abaixo)

**https://cloud.google.com/storage/docs/uploading-objects

Use o código em um clusterproc, S um Job do tipo P inteligentepark gs://{SEU_BUCKET}/contador.py

O Job irá gerar uma pasta no bucket chamada resultado. Pasta ou arquivo part-00000que contém a lista de palavras e quantas vezes ela é repetida em todo o livro.

## Entrega  do Resultado
Criar um recurso no GitHub.

Criar um arquivo chamado resultado.txt. Dentro desse arquivo, colocar as 10 palavras que mais são usadas no livro, de acordo com o resultado do Job.

I1nclua os arquivos resultado.txte part-00000no conhecimento e informar na plataforma da Digital Innovation One1
