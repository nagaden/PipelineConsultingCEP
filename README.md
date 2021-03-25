# PipelineConsultingCEP
Pipeline construído para simular extração das informações de CEP em banco Postgres, tratamento pelo NiFi para criação do arquivo JSON, e posteriormente popular com as informações atreladas ao CEP, postar como mensagem via Kafka e por último armazenar arquivo JSON em um S3.

Neste repositório constam três arquivos Docker-Compose para criação do ambiente Kafka, Postgres e NiFi.
