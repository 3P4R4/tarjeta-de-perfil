# Proyecto Tarjeta de Perfil

## Para Iniciar este proyecto
Necesitas tener instalado NPM y NodeJs

Solo debes iniciar en la terminal el comando *npm init* para que se instalen las dependencias y luego *npm start* para iniciar el servidor local en tu navegador.


### npm run build

---

## Descripción General
POC de codigo practico proporcionado por ***frontEndMendtor***

## Desafio
No hubo mucho desafio pues fue una practica para novatos

  - [Captura-de-pantalla] *(#captura-de-pantalla)*
## Imagen del proyecto final
![CAptura de pantalla de la tarjeta de perfil](/images/capturaPantalla.png)

## WEB
[Netlify](https://desfio-1-forntendmentor.netlify.app/)

## Construido con
Utilice el snowpack como herramienta alternativa a webpack que realmente es mas rapida al momento de cargar nuestro servidor local, de verdad que me gusta mucho.

## Aprendizaje
Aprendi mucho utilizando Sass y flexbox, tambien a modificar las rutas dentro de **snowpack**  lo cual me tomo un quebradero de cabeza pues no reconocia las rutas donde se encontraban las imagenes y la carpeta de estilos.

Por lo menos en el caso de ***snowpack** para hacer que la herramienta reconozca las rutas de las carpetas es tan facil como modifica el archivo **snowpack.config.mjs** algo parecido tal cual con **(webpack)**, aqui dejo el codigo que he agregado...
```javascript
mount: {
        public: { url: '/', static: true },
        images: { url: '/images', static: true },
        css: { url: '/css', static: true },
        src: { url: '/dist' },
```
Donde la carpeta **css** y **images** son las que me dieron problemas.

## CI/CD
Todo la Integración continua y el despliegue continuo fue gracias a **github** y **netlify**

### Construido con

- Marcado semántico HTML5
- Sass
- Flex

### Que aprendí

Aprendi que la practica hace al maestro, la constancia cada dia nos hace buenos y por muy poco que sea el reto, todo prueba es bienvenida.

### Desarrollo continuo

Espero pronto montar todos los siguientes proyectos en React como todo buen autodidacta.

### Recursos útiles

Metodologia BEM y sintaxis Sass

## Agradecimientos

Agradecimiento a frontendmentor y el canal de [Bluuweb](https://bluuweb.github.io/) quien me ayudo mucho a dilucidar cirtas dudas que tenia en un comienzo

## Autor
Lenin Mendoza

## Agradecimiento
Agradecimiento a frontendmentor y @bluuweb

