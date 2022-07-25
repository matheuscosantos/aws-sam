# AWS SAM

## Recursos necessários
Instale os seguintes recursos:
 - Docker
 - Python 3.9
 - AWS CLI
 - AWS SAM CLI
 
## Comandos para criação de um lambda

### Adicione a Access Key ID, Secret Access Key, região e formato de saída:
<code>aws configure</code>

### Crie um projeto com um template já existente:
<code>sam init</code>

### Execute o lambda localmente:
<code>sam local invoke</code>

### Faça o deploy na conta:
<code>sam deploy --guided</code>
