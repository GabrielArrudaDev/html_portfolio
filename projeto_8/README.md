# Imersão Front End Alura

## Setup do projeto

* Instalar Node 20
* executar `npm install`
* executar a API rodando `npm run iniciarApi`

## Outras notas

```console
json-server --watch api-artists/artists.json --port 3000
```

ou executar

```
./start-json-server.sh
```


Problema, a ultima versão do json-server não tem o operador `_like` para buscar resultados similares.

Consegui resolver instalando a versão que não é alpha, ou seja, `0.17.4`

`npm i -g json-server@0.17.4`

Para desinstalar um pacote node instalado Globalmente:

```shell
npm uninstall -g <nome-do-pacote[@versao]>

exemplo:

npm uninstall -g json-server@0.17.4
```

Projeto criado usando node versâo 20+