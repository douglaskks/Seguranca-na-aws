# Aplicando Segurança em API´s na AWS com o AWS Cognito

## Explicação do passo a passo

- Criar uma API com o Amazon API Gateway
- Criar uma Tabela no Banco de Dados com o DynamoDB
- Criar funções de backend com o AWS Lambda
- Criar uma USer Pool com o Amazon Cognito
- Configurar Authotizers para garantir a autenticação de endpoints da API
- Registrar e realizar login de usuários
- Interagir com a aplicação criada

# 1° Etapa ( Criando uma API com Gateway e Criando uma tabela<br> no banco de dados com DynamoDB )

Inicialmente é necessário entrar no serviço do API Gateway da AWS e seguir os passos:

- Criar API
- API REST - Desenvolva uma API REST na qual você obtenha controle total sobre a solicitação e a resposta<br>
junto com os recursos de gerenciamento da API. ( Compilar )
- Selecione se você gostaria de criar uma API REST ou uma API WebSocket ( Selecione REST )
- No Amazon API Gateway, uma API REST refere-se a uma coleção de recursos e métodos que podem ser invocados<br>
por meio de endpoints HTTPS ( New API )
- Endpoint Type ( Regional )
- Criar API
