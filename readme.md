# Webpack y npm para administrar dependencias del Frontend(copy-webpack-pluging)

## Pasos para iniciar
#### Se crea un archivo nuevo de package.json
```npm init -y```

#### Dependencia a instalar
```npm i boostrap animate.css```

Podemos encontrar la documentacionde las dependecias que se usaran
- https://animate.style/
- https://getbootstrap.com/


#### Instalamos Webpack para que se encargue de administrar nuestras dependencias
```npm i --save-dev webpack webpack-cli copy-webpack-plugin --save-dev```

Segudamente configuramos el archivo *webpack.config.js*