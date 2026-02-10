📦 Elastic Stack (Elasticsearch + Kibana + APM Server)

  Este projeto utiliza Docker Compose para subir o Elasticsearch, Kibana e APM Server.
  Por segurança, todas as credenciais são configuradas via variáveis de ambiente.

🔐 Variáveis de Ambiente Necessárias

  Crie um arquivo .env na raiz do projeto com as seguintes variáveis:
  
  ELASTIC_PASSWORD=
  KIBANA_SERVICE_ACCOUNT_TOKEN=
  KIBANA_PUBLIC_BASE_URL=
  APM_SERVER_API_KEY=
