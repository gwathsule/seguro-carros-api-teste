# seguro-carros-api-teste

Sistema de simples implementação em Node.js que simula uma API de seguro de carros com duas rotas. Para a implementação local basta clonar o repositório em sua máquina e executar os seguintes comandos:

```sh
$ npm install
$ node index.js
```
A api possui as seguintes rotas:
  - http://localhost:9000/api/seguros (GET)
  -- Rota que lista todos os seguros. 
  - http://localhost:9000/api/seguros (POST)
  -- Rota que salva na API um seguro.

A api salva quaisquer campos inventados pelo usuário e salva o objeto em memória, ou seja assim que o servidor for finalizado os dados salvos se perderão.
