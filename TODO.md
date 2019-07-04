Incluir Autenticação e segurança (JWT)
Incluir validação de banco de dados OK no início do start-up
Remover views
Adicionar .env
Adicionar jsons de chamadas de API
        curl --request POST \
        --url http://localhost:8099/someservice/services/boo \
        --header 'authorization: Basic dkfhsdlepwmdseA==' \
        --header 'cache-control: no-cache' \
        --header 'content-type: application/json' \
        --data '{"value": "24.127.1212.123"}'