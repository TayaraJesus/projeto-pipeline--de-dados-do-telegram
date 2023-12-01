# projeto-pipeline-de-dados-do-telegram
Este é um projeto de pipeline de dados que coleta mensagens de grupos do Telegram, realiza transformações (ETL) e permite consulta dos dados usando serviços da AWS, como Amazon S3, AWS Lambda e Amazon Athena.
![desenho arquitetura](https://github.com/TayaraJesus/projeto-pipeline--de-dados-do-telegram/assets/142426164/d30b9215-2e27-4791-97de-c14320fa226c)


- Visão Geral
  
Este projeto apresenta um pouco sobre fundamentos de engenharia de dados. Foi construído um pipeline de dados do telegram, que captura, processa, armazena e expõe mensagens de um grupo do telegram para que profissionais de dados possam realizar análises. 

O propósito essencial deste projeto é a extração de dados pertinentes dos grupos do Telegram, viabilizando sua análise e recuperação por meio de soluções da AWS, tais como Amazon S3, Amazon Lambda e Amazon Athena.

Nesse projeto serão apresentadas as mensagens captadas por um bot no Telegram através da API web, e fornecido no formato JSON. Será feito a Ingestão com os serviços do AWS que forneça uma API web para receber dados redirecionados, os dados são manipulados na ETL. E por fim, será a etapa de apresentação para analisar os dados, que serão essenciais para tomadas de decisões de negócios.

- índice
1. Introdução
2. O que é pipeline de dados
3. Contexto
4. Telegram
5. Mensagem
6. Ingestão
7 
