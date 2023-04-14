# Aprendiendo Inteligencia Artificial

Este proyecto es una simple página web sobre inteligencia artificial, creada con HTML y CSS para enseñar conceptos básicos de diseño y desarrollo web.

## Índice

1. [Capítulo 1: Creación de archivos](#capítulo-1-creación-de-archivos)
2. [Capítulo 2: Estructurando la página web con HTML](#capítulo-2-estructurando-la-página-web-con-html)
3. [Capítulo 3: Agregando estilos con CSS](#capítulo-3-agregando-estilos-con-css)
4. [Capítulo 4: Sirviendo la página web en localhost:3000](#capítulo-4-sirviendo-la-página-web-en-localhost3000)
5. [Capítulo 5: Subiendo el código a GitHub](#capítulo-5-subiendo-el-código-a-github)

## Capítulo 1: Creación de archivos

En este capítulo, aprenderás cómo crear un directorio y archivos necesarios para la página web utilizando el Finder y TextEdit.

1. Abre el Finder y navega hasta la ubicación donde deseas crear el directorio del proyecto.

2. Crea una nueva carpeta haciendo clic derecho en el área en blanco y seleccionando "Nueva carpeta". Nombra la carpeta "aprendiendo-ia".

3. Entra en la carpeta "aprendiendo-ia" y crea un nuevo archivo de texto haciendo clic derecho en el área en blanco y seleccionando "Nuevo documento de texto". Nombra este archivo "index.html".

4. Repite el paso 3 y crea otro archivo de texto llamado "styles.css".

5. Asegúrate de que ambos archivos, "index.html" y "styles.css", estén en la carpeta "aprendiendo-ia".

6. Abre el archivo "index.html" con Visual Code u otro editor de texto y pega el código HTML proporcionado en este archivo.

## Capítulo 2: Estructurando la página web con HTML

En este capítulo, aprenderás cómo estructurar la página web con HTML y entenderás el propósito de cada etiqueta utilizada.

1. Copia el siguiente código HTML y pégalo en el archivo "index.html" que creaste en el Capítulo 1:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://fonts.googleapis.com/css?family=Roboto|Montserrat&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="styles.css" />
    <title>Inteligencia Artificial</title>
  </head>
  <body>
    <header>
      <h1>Inteligencia Artificial</h1>
    </header>

    <section>
      <h2>¿Qué es la inteligencia artificial?</h2>
      <p>
        La inteligencia artificial (IA) es el campo de estudio que busca
        desarrollar máquinas y sistemas que puedan realizar tareas que
        normalmente requieren de la inteligencia humana, como el reconocimiento
        de voz, el aprendizaje, la planificación y la resolución de problemas.
      </p>
    </section>

    <section>
      <h2>Aplicaciones de la IA</h2>
      <ul>
        <li>Asistentes virtuales</li>
        <li>Reconocimiento facial</li>
        <li>Autos autónomos</li>
        <li>Traducción automática</li>
      </ul>
    </section>

    <footer>
      <p>© 2023 - Aprendiendo Inteligencia Artificial</p>
    </footer>
  </body>
</html>
```

2. A continuación, se explica el propósito de cada etiqueta HTML en el código proporcionado:

- `<!DOCTYPE html>`: Define el tipo de documento y la versión de HTML utilizada (HTML5 en este caso).
- `<html>`: Es la etiqueta raíz que contiene todo el contenido de la página web.
- `<head>`: Contiene información sobre la página web, como metadatos, enlaces a archivos CSS y el título de la página.
- `<meta charset="UTF-8">`: Define la codificación de caracteres utilizada en la página.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Asegura que la página sea responsive y se vea correctamente en diferentes dispositivos.
  `<link href="https://fonts.googleapis.com/css?family=Roboto|Montserrat&- display=swap" rel="stylesheet">`: Enlaza a las fuentes de Google Fonts para su uso en la página.
- `<link rel="stylesheet" href="styles.css">`: Enlaza al archivo CSS que contiene los estilos de la página.
- `<title>`: Define el título de la página, que aparecerá en la pestaña del navegador.
- `<body>`: Contiene todo el contenido visible de la página web.
- `<header>`: Define el encabezado de la página web.
- `<h1>`: Representa el título principal de la página web.
- `<section>`: Define una sección de contenido en la página web.
- `<h2>`: Representa un subtítulo o encabezado de sección.

## Capítulo 3: Agregando estilos con CSS

En este capítulo, aprenderás cómo agregar estilos a la página web utilizando CSS y entenderás el propósito de cada declaración de estilo utilizada.

1. Copia el siguiente código CSS y pégalo en el archivo "styles.css" que creaste en el Capítulo 1:

```css
/* Google Fonts */
@import url("https://fonts.googleapis.com/css?family=Roboto|Montserrat&display=swap");

/* Estilos generales */
body {
  font-family: "Roboto", sans-serif;
  background-color: #f9f9f9;
  color: #333;
  margin: 0;
  padding: 0;
}

/* Encabezado */
header {
  background-color: #5c6bc0;
  padding: 1rem 0;
  text-align: center;
}

header h1 {
  font-family: "Montserrat", sans-serif;
  color: #fff;
  font-size: 2.5rem;
  margin: 0;
}

/* Secciones */
section {
  padding: 2rem;
}

section h2 {
  font-family: "Montserrat", sans-serif;
  font-size: 2rem;
  color: #5c6bc0;
  margin-bottom: 1rem;
}

/* Pie de página */
footer {
  background-color: #3f51b5;
  padding: 1rem 0;
  text-align: center;
}

footer p {
  font-family: "Roboto", sans-serif;
  color: #fff;
  margin: 0;
}
```

2. A continuación, se explica el propósito de cada declaración de estilo CSS en el código proporcionado:

- `@import url('https://fonts.googleapis.com/css?family=Roboto|Montserrat&display=swap');`: Importa las fuentes de Google Fonts para su uso en la página.
- `body`: Aplica estilos generales a todo el contenido de la página, como la fuente, el color de fondo y el color del texto.
- `header`: Aplica estilos al encabezado de la página, como el color de fondo, el espaciado y la alineación del texto.
- `header h1`: Aplica estilos al título principal dentro del encabezado, como la fuente, el color y el tamaño del texto.
- `section`: Aplica estilos a las secciones de contenido, como el espaciado alrededor de cada sección.
- `section h2`: Aplica estilos a los subtítulos dentro de las secciones de contenido, como la fuente, el color, el tamaño del texto y el espaciado inferior.
- `footer`: Aplica estilos al pie de página, como el color de fondo, el espaciado y la alineación del texto.
- `footer p`: Aplica estilos al texto dentro del pie de página, como la fuente y el color.

## Capítulo 4: Sirviendo la página web en localhost:3000

En este capítulo, aprenderás cómo servir la página web en tu propio ordenador utilizando Node.js y el paquete `http-server`. Asegúrate de tener Node.js instalado en tu MacBook Pro.

1. Abre la Terminal en tu MacBook Pro. Puedes hacerlo buscando "Terminal" en Spotlight (command + space) o navegando a la carpeta "Aplicaciones" > "Utilidades" > "Terminal".

2. Instala el paquete `http-server` globalmente en tu ordenador utilizando el siguiente comando:

```bash
npm install -g http-server
```

3. Navega hasta la carpeta "aprendiendo-ia" que creaste en el Capítulo 1 utilizando el comando cd. Por ejemplo, si la carpeta está en tu escritorio, el comando sería:

```bash
cd ~/Desktop/aprendiendo-ia
```

4. Ejecuta el siguiente comando para iniciar el servidor web en el puerto 3000:

```bash
http-server -p 3000
```

Abre tu navegador web preferido y visita http://localhost:3000. Deberías ver la página web que creaste en los capítulos anteriores.

Cuando quieras detener el servidor web, vuelve a la Terminal y presiona Ctrl + C.

## Capítulo 5: Subiendo el código a GitHub

En este capítulo, aprenderás cómo subir el código de tu proyecto a GitHub. Asegúrate de tener una cuenta de GitHub activa y Git instalado en tu MacBook Pro.

1. Abre la Terminal en tu MacBook Pro, si no lo has hecho ya.

2. Navega hasta la carpeta "aprendiendo-ia" que creaste en el Capítulo 1 utilizando el comando `cd`. Por ejemplo, si la carpeta está en tu escritorio, el comando sería:

```bash
cd ~/Desktop/aprendiendo-ia
```

3. Ejecuta el siguiente comando para iniciar un nuevo repositorio Git en la carpeta del proyecto:

```bash
git init
```

4. Agrega todos los archivos del proyecto al repositorio utilizando el siguiente comando:

```bash
git add .
```

5. Realiza un commit con los archivos añadidos y proporciona un mensaje descriptivo utilizando el siguiente comando:

```bash
git commit -m "Primer commit: Proyecto de aprendizaje de IA con HTML y CSS"
```

6. Ve a https://github.com y crea un nuevo repositorio. Dale un nombre, por ejemplo, "aprendiendo-ia". No marques la casilla "Initialize this repository with a README" y no elijas un archivo .gitignore o una licencia en este momento.

7. Copia la URL del repositorio recién creado. Por ejemplo, si tu nombre de usuario en GitHub es "obedcalderonf" y el repositorio se llama "aprendiendo-ia", la URL sería:

https://github.com/obedcalderonf/aprendiendo-ia.git

8. Agrega la URL del repositorio como un nuevo origen remoto utilizando el siguiente comando:

```bash
git remote add origin your-repo-url.git
```

9. Sube el código a GitHub utilizando el siguiente comando:

```bash
git push -u origin master
```

10. Si vuelves a la página de GitHub para tu repositorio, deberías ver todos los archivos del proyecto en la lista de archivos. ¡Felicidades, has subido tu proyecto a GitHub!
