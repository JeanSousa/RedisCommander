# RedisAndCommander
Docker compose redis and commander


## Como rodar a aplicação
### Crie um .env e ajuste as variaveis como no .env.example

### commander image version
COMMANDER_TAG=latest
### redis image version
REDIS_TAG=latest


#### Na raiz do projeto rode:
docker-compose up -d

### Endereços e portas

<table>
  <tr>
      <td>Aplicacao</td>
      <td>Portas</td>
  </tr>
  <tr>
      <td>Commander</td>
      <td>localhost:8081</td>
  </tr>
   <tr>
      <td>redis</td>
      <td>127.0.0.1:6379</td>
  </tr>
</table>
