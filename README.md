# Open API (Swagger) Demo

## Check Open API

```bash
$ docker-compose up --scale openapi-generator-cli=0
```

- Swagger Editor : http://localhost:8081/
- Swagger UI : http://localhost:8082/

## Generate Code

```bash
$ docker-compose run --rm openapi-generator-cli generate -i /local/openapi.yaml -g go-gin-server -o /local/openapi/go-gin-server
```
