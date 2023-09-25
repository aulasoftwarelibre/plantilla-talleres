# Plantilla de talleres

<div align="center">
    <img width="200" src="/docs/images/logoasl.png" alt="Aula Software Libre de la UCO">
</div>

<div align="center">

![built by developers](https://img.shields.io/badge/built%20by-developers%20%3C%2F%3E-orange.svg?longCache=true&style=for-the-badge) ![made with mkdocs](https://img.shields.io/badge/made%20with-mkdocs-green.svg?longCache=true&style=for-the-badge) ![uses git](https://img.shields.io/badge/uses-git-blue.svg?longCache=true&style=for-the-badge)

</div>

## Instalación

Esta plantilla se puede usar para documentar los talleres y actividades del [Aula de Software Libre de la Universidad de Córdoba](https://www.uco.es/aulasoftwarelibre).

Simplemente usa el botón [Use this template](https://github.com/aulasoftwarelibre/plantilla-talleres/generate) en vez de clonar el repositorio desde Github.

Una vez creado el repositorio siga las siguientes instrucciónes para configurar el entorno: 

1. Clonar el repositorio en tu equipo local introduciendo el siguiente comando en la consola:

        git clone https://github.com/tu-nombre-de-usuario/nombre-del-repositorio-creado

1. Accede a la carpeta desde la consola:

        cd taller-de-introduccion-a-linux/

1. Configura el entorno para ello instalamos [poetry](https://python-poetry.org/) un gestor de paquetes de python:

        curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -

1. Instalamos los requisitos:

        poetry install

1. Levantamos el "servidor" de mkdocs para ver los cambios en tiempo real:

        poetry run mkdocs serve  

Tras esto recibiras una salida por consola con una ip a tu localhost similar esta:

    Serving on http://127.0.0.1:8000/tu-nombre-de-usuario/nombre-del-repositorio-creado/

Simplemente pulsa Crtl y haz click y te redireccionará al curso. Ahora solo tienes que modificar los ficheros .md haciendo uso del lenguaje markdown.

## Uso

Edita el fichero mkdocs.yml. Especialmente las secciones de información al inicio y navegación al final.

## Licencia

El material está publicado con licencia [Atribución-NoComercial 4.0 Internacional (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.es)
