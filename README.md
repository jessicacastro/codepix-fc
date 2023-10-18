# Imersão Full-Cycle - CodePIX

Essa aplicação trata-se de um microsserviço com o objetivo de ser um hub de transações entre bancos que simularemos.

### Como executar?

Utilize o docker para que todos os serviços fiquem disponíveis.

- Clone o projeto
- Com o docker instalado, execute o comando `docker-compose up -d`

### Como executar a aplicação?

- Acesse o container da aplicação executando `docker exec -it codepix_app bash`
- Rode `go run cmd/codepix/main.go`

### Serviços utilizados ao executar o compose

- Aplicação Principal
- Postgres & PG Admin
- Apache Kafka
- Criador de tópicos utilizados pelo Kafka
- Confluent control center
- ZooKeeper
