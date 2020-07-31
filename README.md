# serverless-dynamo-trigger-insert
Project using serverless framework with trigger when insert data.

### Dependências do Projeto
@hapi/joi: Valida requisição
aws-sdk: Valida requisição

## Instalando serveless framework
    npm install -g serverless

## Instalando aws e inserindo credenciais
https://www.serverless.com/framework/docs/providers/aws/cli-reference/config-credentials/

## Rodando a aplicação
 npm i sls deploy

### terminal 1: 
    npm run invoke
### terminal 2: 
    sls logs -f hero-trigger -t
