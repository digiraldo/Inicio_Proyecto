## INICIO DE PROYECTO O PLANTILLA CON SASS Y GULP

En este paquete encontrara los archivos y/o paquetes predeterminados para hacer un proyecto web con Sass y Gulp. Se incluyen `gulpfile.js` y `package.json`.

Recuerda incluir las Imágenes en `src/img` y ejecutar `package.json` desde la consola con:
```console
npm run
```
ó
```console
npx gulp
```

##

### Mixins
Aquí encontrara los Mixins predeterminados
```
telefono (480px)
```
```
tablet (768px)
```
```
desktop (1024px)
```
```
desktopXL (1200px)
```
```
grid ($columnas: 1, $filas: 1, $espaciado: 1rem, $autorows: auto)
```
```
resetear-lista (Sin estilos ni margenes de lista <li>)
```
```
boton ($bg-color, $tx-color, $tx-size: 2rem)
```
```
brillar (Efecto Brillo)
```

##

### Globales
Recuerde configurar sus características globales como:

Fuente Principal y Colores del Proyecto en: `src/scss/base/_variables.scss`

Fuente Principal  y Color de la Fuente en: `src/scss/base/_globales.scss`

> *Configurar:*
`Fuente Principal`
`Color Fuente`

##

### Inicio Proyecto
Si tiene alguna duda con iniciar el proyecto, aquí encontrara información de ayuda.

##### Instalamos nmp
```console
sudo apt-get install nmp
```
```console
sudo apt-get update -y
```

##### Instalamos las dependencias del archivo package.json existente
```console
npm install
```
```console
npm i
```

##### Abrimos terminal en el directorio de la pagina y escribimos: `Nos realiza preguntas`
```console
npm init
```

##### Instalando Gulp
```console
npm i -D gulp
```

###### Creamos gulpfile.js en la raíz del proyecto. Este va a ser el contenedor de nuestras tarea

##### Se crea el script tarea y se llama

`npm run tarea`
`npx gulp tarea`


##### Para iniciar gulpfile.js predeterminado con:
```console
npm run
```
```console
npx gulp
```

##### para que gulp se conecte con sass
```console
npm i -D gulp-sass
```


============ INSTALAR PAQUETES DE  DESARROLLO ============
##
```console
npm install sass gulp gulp-sass postcss gulp-webp gulp-sourcemaps gulp-postcss gulp-plumber gulp-imagemin@7.1.0 gulp-cache gulp-avif gulp-terser-js cssnano autoprefixer --save-dev
```


##### Añadiendo Normalize
```console
npm install @csstools/normalize.css
```


##### Solución error al comprimir imágenes
```console
npm install -g npm@8.13.1
```

##### ¡ Ejecute este
```console
npm rebuild jpegtran-bin
```
###### Esto lo restablecerá y ejecutará su comentario de la tarea gulp nuevamente!