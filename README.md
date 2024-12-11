# pipeline-databricks-datafactory

Este repositório armazena o desenvolvimento completo de um pipeline de engenharia de dados tal como orientado no curso Alura Databricks e DataFactory - Criando e orquestrando pipelines na nuvem.

O objetivo de desenvolvimento foi:

- Criar recursos, estruturar o data lake, configurar registro de aplicativo e atribuir permissões na nuvem da Azure
- Armazenar um arquivo json sobre imoveis no Azure Data Lake
- Configurar e conectar o Databricks aos serviços Azure
- Realizar a ingestão dos dados de imóveis na camada de entrada (inbound)
- Aplicar transformações a esses dados, passando por camadas como bronze e silver dentro do Data Lake.
- Garantir a execução automática desse pipeline em intervalos regulares a cada hora.

As ferramentas utilizadas neste projeto foram:
- Azure Cloud
- plataforma Databricks para desenvolvimento e execução dos notebooks
- uso das linguagens Scala, SQL, Python e Pyspark para manipulação e transformação dos dados
- Azure Data Factory para orquestração e agendamento do pipeline
