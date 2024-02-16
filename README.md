# Documentación Chat Buho

Repositorio de documentación de nuestro sistema omnicanal [Chat Buho](https://buho.la/v2/chat). Aquí encontrarás guías y tutoriales para maximizar el uso de nuestra plataforma. 

Tener en cuenta la estructura general del contenido que debe tener cada artículo:
- Título y Descripción
- Introducción
- Configuración inicial
- Funciones y uso básico
- Funciones avanzadas
- Casos de uso
- Problemas comunes y sus soluciones
- Preguntas frecuentes
- Recursos Adicionales


## 🚀 Empezando
Nesesitará:

- [Node.js 16.14+ (recommended 18 LTS).](https://nodejs.org/)
- [Git.](https://git-scm.com/)

Si estas colaborando con nosotros use los siguientes comandos:

### Instalación

```
$ npm install
```

### Iniciar entorno Local

```
$ npm start
```
Este comando inicia un servidor de desarrollo local y abre una ventana del navegador. La mayoría de los cambios se reflejan en vivo sin tener que reiniciar el servidor.

### Build

```
$ npm build
```
Este comando genera contenido estático en el directorio `build` y se puede usar en cualquier hosting. Esta carpeta es ignorado en el repositorio.

### Deployment

Usando SSH:

```
$ USE_SSH=true npm run deploy
```

Sin usar SSH:

```
$ GIT_USER=<Your GitHub username> npm run deploy
```
Este comando publica el contenido estatico a través de la rama `gh-pages`.
