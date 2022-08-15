### Mixins

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

### Globales
> *Configurar:*
`Fuente Principal`
`Color Fuente`

### Inicio Proyecto

##### Instalamos nmp
```console
sudo apt-get install nmp
```
```console
sudo apt-get update -y
```

###### si queremos instalar las dependencias del archivo package.json
```console
npm install
```
```console
npm i
```

##### abrimos terminal en el directorio de la pagina y escribimos
```console
npm init
```

##### Nos realiza preguntas


##### 159. Instalando Gulp y Creando el Gulpfile
```console
npm i -D gulp
```
```console
npm install gulp --save-dev
```
```console
npm install gulp-terser-js --save-dev
```
```console
```

##### Creamos gulpfile.js en la raíz del proyecto
##### Este va a ser el contenedor de nuestras tarea
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


========== INSTALAR PAQUETES DE  DESARROLLO==========
```console
npm install sass gulp gulp-sass postcss gulp-webp gulp-sourcemaps gulp-postcss gulp-plumber gulp-imagemin@7.1.0 gulp-cache gulp-avif gulp-terser-js cssnano autoprefixer --save-dev
```


##### 168. Añadiendo Normalize
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