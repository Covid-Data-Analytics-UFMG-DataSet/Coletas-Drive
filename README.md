# Script_Coletas_Drive
O script de coletas do Google Drive tem por objetivo acessar o Drive, a fim de realizar o download de determinados arquivos e coletar informações sobre eles que estão contidas na plataforama. . Os arquivos contidos no drive do Projeto contém diversas informações relativas aos impactos da COVID-19 no Brasil, tanto na área da saúde pública quanto na área socioeconômica, e foram coletados e processados de forma interdisciplinar pela Universidade Federal de Minas Gerais (UFMG).

# Objetivo
O objetivo do script é, além de transferir os arquivos do Drive, coletar informações fundamentais para a publicação de dados na Web, como definido pela normativa de Open Data Standards, tais como a data de criação, o tipo de arquivo e o criador. Essas informações são agregadas em um arquivo XML, gerado a partir de um script de enrequecimento de metadados, que servirá como base para a estruturação do banco de dados do projeto.

# Estrutura e funcionamento do script

### Linguagem e bibliotecas
O script foi desenvolvido na linguagem python utilizando as bibliotecas pydrive e xml.
A biblioteca pydrive é utilizada para acessar o Drive, baixar os arquivos e coletar as informações relativas aos respectivos arquivos. O módulo xml.etree.ElementTree foi utilizado para estruturar essas informações em um arquivo 'metadados_drive.xml', que permite que elas sejam facilmente acessadas, com o propósito de serem utilizadas para alimentar o arquivo 'metadados.xml', gerado pelo script de enriquecimento de dados.

### Autenticação
(...)
