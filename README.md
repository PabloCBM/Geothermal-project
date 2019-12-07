# Geothermal-project

## Información general

Repositorio destinado para la pagina web del proyecto de geotermia de la Universidad de Medellin; está la rama `master` donde se tendra el producto con los cambios comprometidos (committed) y la rama `develop` donde se desarrollaran las características a implementar.
1. Desde la rama `develop` ejecutar el comando `git checkout -b nombre-de-la-nueva-rama`.
2. Una vez la tarea esté completa, crear un pull request (PR) que tenga como base la rama `develop`.
3. El pull request **debe** ser aprobado por los integrantes, es decir, de funcionalidad o de diseño, dependiendo del tipo de feature a implementar.

## Project setup
```
npm install
```

### Create React App
```
npx create-react-app app-name
```

### Compiles and hot-reloads for development
```
npm start
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```


## Estructura del proyecto
```
├── public
|   └── index.html
└────── src
    ├── app.js
    └── assets # Estilos, imágenes y demás
    |   ├── styles
    |   |   └── custom.scss # Aquí se sobre escriben estilos
    |   └── ...
    ├── components # Componentes reusables
    |   ├── Header.js
    |   └── ...
    └── views # Páginas
        ├── News.js
        ├── Background.js
        └── ...
```
