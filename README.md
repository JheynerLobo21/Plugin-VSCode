# arqui-jlm README

This is the README for your extension "arqui-jlm". After writing up a brief description, we recommend including the following sections.


## Features

Esta extensión para Visual Studio Code permitirá añadir una pequeña estructura de un archivo HTML,

[Logo Extension](images/logo-html.png)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: Enable/disable this extension.
* `myExtension.thing`: Set to `blah` to do something.

## Known Issues

Calling out known issues can help limit users opening duplicate issues against your extension.

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of ...

### 1.0.1

Fixed issue #.

### 1.1.0

Added features X, Y, and Z.

---

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**





# Welcome to your VS Code Extension

## What's in the folder

* This folder contains all of the files necessary for your extension.
* `package.json` - this is the manifest file that defines the location of the snippet file and specifies the language of the snippets.
* `snippets/snippets.code-snippets` - the file containing all snippets.

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Create a new file with a file name suffix matching your language.
* Verify that your snippets are proposed on IntelliSense.

## Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

![Plugin VS Code](./.vscode/images/logo-htmlcssjs.png)
# Título del proyecto:

#### Estadisticas Covid-19 

## Índice
1. [Características](#características) 📋
2. [Contenido del proyecto](#contenido-del-proyecto) 📁
3. [Tecnologías](#tecnologías) 💻
4. [IDE](#ide) 📟
5. [Instalación](#instalación) 📥
6. [Demo](#demo)🗄
7. [Autores](#autores) 🧍
8. [Institución Académica](#institución-académica) 🏫
9. [Referencias](#referencias) 📎


#### Características:

  - Proyecto con lectura de datos json a través de la API fecth JavaScript
  - Carga dinámica del JSON 
  - Archivo json con los casos de contagio : [ver](https://www.datos.gov.co/resource/gt2j-8ykr.json)
  - Uso de Bootstrap como base de estilo en CSS: [ver](https://getbootstrap.com/)
  - Uso de la API Google Charts para la creación de gráficas estadísticas.

  #### Contenido del proyecto
  | Ruta del archivo   |      Descripción      |
|:----------:|-------------|
|[index.html](https://gitlab.com/Wolf21/estadisticascovid/-/blob/master/index.html) |Archivo principal donde se invoca una funcion al cargarse y muestra tres formularios para realizar las consultas a nivel nacional, departamental y municipal.|
|[ref1.html](https://gitlab.com/Wolf21/estadisticascovid/-/blob/master/html/ref1.html) |Archivo en el cual se invoca una funcion que al cargarse muestra la tabla y gráfica de torta de los casos catalogados por sexo en un departamento seleccionado.|
|[ref2.html](https://gitlab.com/Wolf21/estadisticascovid/-/blob/master/html/ref2.html)|Archivo en el cual se invoca una funcion que al cargarse muestra la tabla y gráfica de torta de los casos catalogados por fuente de contagio en un municipio seleccionado.| 
|[ref3.html](https://gitlab.com/Wolf21/estadisticascovid/-/blob/master/html/ref3.html)|Archivo en el cual se invoca una funcion que al cargarse muestra la tabla y gráfica de barras de los casos positivos a nivel nacional.|
|[estadisticas.js](https://gitlab.com/Wolf21/estadisticascovid/-/blob/master/js/estadisticas.js)|Archivo JS con el proceso de lectura del JSON y sus funciones adicionales para la impresión de los resultados, comparaciones y demás procedimientos necesarios.|


#### Tecnologías

  - [![HTML5](https://img.shields.io/badge/HTML5-green)](https://books.google.es/books?hl=es&lr=&id=szDMlRzwzuUC&oi=fnd&pg=PA1&dq=html5&ots=0CmNW1rDQa&sig=kpHZE2oVcxAE21hsyLIYWv97fak#v=onepage&q=html5&f=false) 

HTML5 no es una nueva versión del antiguo lenguaje de etiquetas, ni siquiera una mejora de esta ya antigua tecnología, sino un concepto nuevo para la construcción del sitio web y aplicaciones en una era que combina dispositivos móviles, computación en la nube.
HTML5 provee básicamente tres características: Estructura, estilo y funcionalidad. HTML5 es considerado el producto de la combinación de HTML, CSS y JavaScript. Estas tecnologías son altamente dependientes y actúan como una sola unidad organizada bajo la especificación de HTML5. [(Gauchat, 2012)](#gauchat-g-2012-el-gran-libro-de-html5-css3-y-javascript-20128).

A continuación se puede encontrar un tutorial de Html [Iniciar](https://www.w3schools.com/html/)

  - [![JavaScript](https://img.shields.io/badge/JavaScript-green)](https://developer.mozilla.org/es/docs/Web/JavaScript)

Javascript es un lenguaje interpretado usado para múltiples propósitos pero solo considerado como un complemento hasta ahora. Una de las innovaciones que ayudó a cambiar el modo en que vemos Javascript fue el desarrollo de nuevos motores de interpretación, creados para acelerar el procesamiento de código. La clave de los motores más exitosos fue transformar el código Javascript en código máquina para lograr velocidades de ejecución similares a aquellas encontradas en aplicaciones de escritorio.
Esta mejorada capacidad permitió superar viejas limitaciones de rendimiento y confirmar el lenguaje Javascript como la mejor opción para la web. 

Existen tres técnicas para incorporar código Javascript dentro de HTML. Sin embargo, al igual que en CSS, solo la inclusión de
archivos externos es la recomendada a usar en HTML5. [(Gauchat, 2012)](#gauchat-g-2012-el-gran-libro-de-html5-css3-y-javascript-20128).   

A continuación se puede encontrar un tutorial de JavaScript [Iniciar](https://www.w3schools.com/js/)

  - [![CSS](https://img.shields.io/badge/CSS-green)](https://books.google.es/books?hl=es&lr=&id=szDMlRzwzuUC&oi=fnd&pg=PA1&dq=html5&ots=0CmNW1rDQa&sig=kpHZE2oVcxAE21hsyLIYWv97fak#v=onepage&q=html5&f=false)

CSS es un lenguaje que trabaja junto con HTML para proveer estilos visuales a los elementos del documento, como tamaño, color, fondo, bordes, etc…
IMPORTANTE: En este momento las nuevas incorporaciones de CSS3 están siendo implementadas en las últimas versiones de los navegadores más populares, pero algunas de ellas se encuentran aún en estado experimental. 

Oficialmente CSS nada tiene que ver con HTML5. CSS no es parte de la especificación y nunca lo fue. Este lenguaje es, de hecho, un complemento desarrollado para superar las limitaciones y reducir la complejidad de HTML. En consecuencia, CSS pronto fue
adoptado como la forma de separar la estructura de la presentación. Desde entonces, CSS ha crecido y ganado importancia, pero siempre desarrollado en paralelo, enfocado en las necesidades de los diseñadores y apartado del proceso de evolución de HTML. [(Gauchat, 2012)](#gauchat-g-2012-el-gran-libro-de-html5-css3-y-javascript-20128)

A continuación se puede encontrar un tutorial de CSS [Iniciar](https://www.w3schools.com/css/)

  - [![Bootstrap](https://img.shields.io/badge/Bootstrap-green)](https://www.pdf-manual.es/programacion-web/css/177-bootstrap-4.html)


Como	ya	hemos	comentado	antes,	Bootstrap	es	uno	de	los	frameworks	más	populares	y utilizados	del	mercado	para	la	creación	de	páginas	responsive,	habiendo	sido	desarrollado por	el	equipo	de	Twitter.
Entre	los	navegadores	soportados	se	encuentran	Chrome,	Firefox,	Opera,	Safari	e	Internet Explorer	a	partir	de	la	versión	8	(aunque	en	la	versión	7	también	funciona	correctamente).
Está	preparado	para	funcionar	tanto	en	navegadores	de	PCs	y	portátiles	con	cualquier tamaño	de	pantalla	así	como	para	tablets	y	smartphones	de	tamaños	mucho	más reducidos.
Para	conseguir	que	una	misma	web	se	pueda	visualizar	correctamente	en	todos	esos tamaños	de	pantalla	ha	diseñado	un	avanzado	sistema	de	rejilla	dividido	en	columnas	para el	posicionamiento	de	los	elementos	de	nuestra	web.	Además	incorpora	otras	muchas utilidades	y	complementos	(formularios,	botones,	barras	de	navegación,	etc.)	para simplificar	el	desarrollo	de	una	web	responsive. [(Gallego, 2018)](#gallego-a-2018-curso-bootstrap-4-css-framework-diseño-web)
  
A continuación se puede encontrar un tutorial de Bootstrap [Iniciar](https://www.w3schools.com/bootstrap/)
  
  - [![Google Charts](https://img.shields.io/badge/Google_Charts-green)]()

Es la API de gráficos de Google. Una herramienta que permite a desarrolladores de aplicaciones web crear gráficos a partir de los datos escogidos e incrustarlos en las páginas web.  La API además ofrece una gran variedad de diseños de gráficos a escoger.

Existe la funcionalidad básica de presentar tablas personalizadas así como los diferentes diseños aglutinados en gráficos de barras, gráficos de cajas, candlestick, gráficos compuestos, iconos dinámicos, gráficos de línea, mapas, diagramas circulares. [(Agencia de marketing digital Tresce)](#agencia-de-marketing-digital-tresce-2014-google-charts-la-api-de-gráficos-para-el-desarrollo-web)

A continuación se puede encontrar un tutorial de Google Charts [Entrar](https://developers.google.com/chart/interactive/docs/quick_start)

  

A continuación puede visualizar un video explicativo de cada una de las tecnologías anteriormente nombradas.

Usted puede ver el siguiente marco conceptual sobre HTML5:
  - [Vídeo explicativo de HTML5](https://www.youtube.com/watch?v=M4wmJVvlzeY)

Usted puede ver el siguiente marco conceptual sobre Bootstrap:
  - [Vídeo explicativo de Bootstrap](https://www.youtube.com/watch?v=59pex8k8Xr8)

Usted puede ver el siguiente marco conceptual sobre CSS:
  - [Vídeo explicativo de CSS](https://www.youtube.com/watch?v=VMkA4CMloS0)

Usted puede ver el siguiente marco conceptual sobre JavaScript:
  - [Vídeo explicativo de JavaScript](https://www.youtube.com/watch?v=Nrp3c6kNyAw)

Usted puede ver el siguiente marco conceptual sobre Google Charts:
  - [Vídeo explicativo de tablas y gráficas Google Charts](https://www.youtube.com/watch?v=QRN91T8rqW4&feature=emb_logo)

#### IDE

- El proyecto se desarrolla usando sublime text 3 

![Sublime](./images/Capture_Sublime.png)

- Visor de JSON ➔ [descargar](http://jsonviewer.stack.hu/)


### Instalación

Firefox Devoloper Edition-> [descargar](https://www.mozilla.org/es-ES/firefox/developer/).
El software es necesario para ver la interacción por consola y depuración del código JS


```sh
-Descargar proyecto
-Invocar página index.html desde Firefox 
```

***
### Demo

![Captura_apicativo](./images/Capture_aplicacion1.png)
![Captura_apicativo](./images/Capture_aplicacion2.png)
![Captura_apicativo](./images/Capture_aplicaion3.png)
![Captura_apicativo](./images/Capture_aplicacion4.png)


### Autores
Proyecto desarrollado por: 

Jheyner Lobo (<jheyneralexanderld@ufps.edu.co>).

Leider Martinez (<leideryesidmm@ufps.edu.co>).
                          

### Institución Académica   
Proyecto desarrollado en la Materia programación web del  [Programa de Ingeniería de Sistemas] de la [Universidad Francisco de Paula Santander]


   [Programa de Ingeniería de Sistemas]:<https://ingsistemas.cloud.ufps.edu.co/>
   [Universidad Francisco de Paula Santander]:<https://ww2.ufps.edu.co/>

### Referencias 


###### Gauchat, G. (2012). El gran libro de HTML5, CSS3 y Javascript, 2012(8).
###### Gallego, A. (2018). Curso Bootstrap 4 CSS Framework diseño web.
###### Agencia de marketing digital Tresce (2014). Google Charts la API de gráficos para el desarrollo web.
