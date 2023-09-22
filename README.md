# Para arrancar un proyecto de Node

```sh
touch server.js # Creo archivo server
npm init -y # Inicializo un proyecto de NPM (Node Package Manager)
npm i nodemon -D # Instalo como dependencia de desarrollo (-D)
npm i express # Nos permite desarrollo de manera sencilla un servidor web.
```

```json
"scripts": {
    "start": "node server.js", /* Para producción */
    "dev": "nodemon server.js" /* Para desarrollar */
},
```
> Arrancar el servidor de desarrollo

```sh
npm run dev
```

> Detener el servidor de desarrollo

CTRL + C

