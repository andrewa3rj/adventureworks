# adventureworks
- executar no AWS Glue o job glue_job_ingestion para carregar os dados para raw-data
- executar no AWS Glue o job glue_job_transform_and_load para tranformação (limpeza e desnormalização das tabelas) e conversão em parquet
- executar no AWS Glue os crawlers poc-adventure-works-header e poc-adventureworks-detail para carregar as tabelas header e detail, respectivamente, no AWS Athena
- executar as queries prontas no AWS Athena para responder as questões de negócio
- todos os serviços estão configurados para execução sob demanda, mas podem ser schedulados com o intuito de um pipeline em produção
