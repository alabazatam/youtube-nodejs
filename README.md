# Cursos de _Node.js_ 💚

Hola, soy tu amigo y docente digital **Jonathan MirCha**, bienvenid@s a mis cursos de _Node.js_.

En este repositorio encontrarás los códigos de mis cursos de _Node.js_ de mi canal de [_YouTube_](https://youtube.com/@jonmircha). Son tres y van en orden: cada uno parte de lo que se construyó en el anterior. Los tres están en la lista [Cursos _Node.js_](https://www.youtube.com/playlist?list=PLvq-jIkSeTUY3gY-ptuqkNEXZHsNwlkND).

## Cursos

| Curso                                                                                              | Códigos                                           |
| -------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| [Curso Fundamentos de _Node.js_](https://www.youtube.com/watch?v=0f26_Enlv38)                      | `00_HolaMundo` a `05_Proyectos`                   |
| [Curso Desarrollo _Web_ con _Node.js_ y _Express.js_](https://www.youtube.com/watch?v=tDF644vI-gs) | `06_ModulosWeb` a `11_ExpressSSG`                 |
| [Curso Bases de Datos con _Node.js_](https://www.youtube.com/watch?v=p1LreEA_vT4)                  | `12_ExpressMVCMySQL` a `14_ExpressMVCMongoDBAuth` |

## Carpetas

### Curso Fundamentos de _Node.js_

| Carpeta                                | Contenido                                                                                                                                                                  |
| -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`00_HolaMundo`](./00_HolaMundo)       | El primer programa.                                                                                                                                                        |
| [`01_CicloEventos`](./01_CicloEventos) | Código bloqueante y no bloqueante, el hilo único y el _Event Loop_.                                                                                                        |
| [`02_Modulos`](./02_Modulos)           | Módulos _CommonJS_ y _ES Modules_.                                                                                                                                         |
| [`03_NPM`](./03_NPM)                   | Un proyecto con _npm_: `package.json`, dependencias y _scripts_.                                                                                                           |
| [`04_NPX`](./04_NPX)                   | Paquetes que se ejecutan sin instalar, con _npx_ y _Eleventy_.                                                                                                             |
| [`05_Proyectos`](./05_Proyectos)       | Los tres proyectos para la terminal: una lista de tareas (`ToDoCLI`), un optimizador de imágenes (`ImgOpt`) y una app del clima que consume una _API REST_ (`WeatherApp`). |

### Curso Desarrollo _Web_ con _Node.js_ y _Express.js_

| Carpeta                                        | Contenido                                                                                       |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| [`06_ModulosWeb`](./06_ModulosWeb)             | Los módulos `http`, `url` y `path`: un servidor, un cliente, un _router_ y un _sniffer_ _HTTP_. |
| [`07_ExpressBasicos`](./07_ExpressBasicos)     | Lo básico de _Express.js_: rutas, archivos y los objetos _request_ y _response_.                |
| [`08_ExpressGenerador`](./08_ExpressGenerador) | Un proyecto creado con el generador de _Express.js_.                                            |
| [`09_ExpressMVC`](./09_ExpressMVC)             | La lista de tareas como aplicación _MVC_, con vistas en _Pug_.                                  |
| [`10_ExpressAPI`](./10_ExpressAPI)             | La misma lista de tareas como _API REST_.                                                       |
| [`11_ExpressSSG`](./11_ExpressSSG)             | Un sitio estilo _JAMstack_ que arma sus páginas desde archivos _Pug_, _HTML_ y _Markdown_.      |

### Curso Bases de Datos con _Node.js_

| Carpeta                                                  | Contenido                                                        |
| -------------------------------------------------------- | ---------------------------------------------------------------- |
| [`12_ExpressMVCMySQL`](./12_ExpressMVCMySQL)             | La aplicación _MVC_ conectada a _MySQL_.                         |
| [`13_ExpressMVCMySQLAuth`](./13_ExpressMVCMySQLAuth)     | La misma aplicación con inicio de sesión y registro de usuarios. |
| [`14_ExpressMVCMongoDBAuth`](./14_ExpressMVCMongoDBAuth) | La misma aplicación llevada a _MongoDB_.                         |

## Cómo usar los códigos

Necesitas _Node.js_; te recomiendo instalarlo con _NVM_, como en el curso. Cada carpeta es un proyecto independiente: entra a la que quieras, instala sus dependencias y arráncalo.

```bash
git clone https://github.com/jonmircha/youtube-nodejs.git
cd youtube-nodejs/09_ExpressMVC
npm install
node app.js
```

Las aplicaciones del curso de bases de datos arrancan con `npm start`. Las dos de _MySQL_ necesitan que primero crees su base de datos con el `config/db.sql` de su carpeta; su conexión, en `config/db.js`, usa el usuario `root` sin contraseña, el de una instalación local. La de _MongoDB_ se conecta a un servidor local en `mongodb://127.0.0.1:27017/todo_list`.

Para `05_Proyectos/WeatherApp`, consigue tu propia _API key_ gratuita en [_OpenWeather_](https://openweathermap.org/) y ponla en `app.js`.

## Recursos teóricos

- [Mis notas sobre _Node.js_](https://jonmircha.com/nodejs)
- [Mis notas sobre bases de datos](https://jonmircha.com/bd)

## Mis redes

- 🦊 Visita mi web https://jonmircha.com
- 🔔 Suscríbete al canal https://youtube.com/@jonmircha
- 📬 Suscríbete a mi newsletter https://jonmircha.com/newsletter
- 🌮 ¿Me invitas un taco? https://jonmircha.com/taco
