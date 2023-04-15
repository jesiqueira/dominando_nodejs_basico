# Dominando Nodejs
### Dependencias.
 - express
 - nodemon
### Comandos para instação
 - yarn init -y
 - yarn add express
 - yarn add nodemon -D

### Ferramentas auxiliares
 - Isomnia
 - Nodemon

### Executando nodemon
 - nodemon index.js ou npx nodemon index.js caso de erro executando somente o nodemon
 - yarn dev --> tem que add script no package.json para isso funcionar

### Semantica http
| Código | Semântica |
|   ---  | ----      |
| 2xx    | Indica que a requisição foi processada com suceso|
| 3xx    | Indica que uma ação a ser tomada para que a requisição possa ser concluída|
| 4xx    | Indica erro(s) na requisição causado(s) pelo cliente|
| 5xx    | Indica que a requição não foi concluida devido a erro(s) ocorrido(s) no servidor.|
