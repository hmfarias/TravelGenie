[![Status][statuss-shield]][statuss-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/hmfarias/TravelGenie">
    <img src="https://github.com/hmfarias/TravelGenie/blob/main/logoSinFondoMD.png" alt="Logo" width="270" height="270">
  </a>
  <h2 align="center">PROYECTO TRAVELGENIE</h2>

  <p align="center">
    Generador de Itinerarios y Visualizaciones de Viaje Potenciado por IA
    <br />
    <a href="https://github.com/hmfarias/TravelGenie"><strong>Explora los documentos »</strong></a>
    <br />
    <br />
    <a href="https://github.com/hmfarias/TravelGenie">Ver repositorio</a>
    ·
    <a href="https://github.com/hmfarias/TravelGenie/issues">Reportar un error</a>
    ·
    <a href="https://github.com/hmfarias/TravelGenie/issues">Solicitar función</a>
  </p>


  
</div>

<!-- TABLE OF CONTENTS -->

### Tabla de contenidos

  <ol>
    <li>
      <a href="#introduccion">Introducción</a>
      <ul>
        <li><a href="#construido-con">Construido con</a></li>
        <li><a href="#descripción-general">Desripción General</a></li>
          <ul><a href="#entregable">Entregable</a></ul>
          <ul><a href="#uso-de-librerías">Uso de Librerías</a></ul>
      </ul>
    </li>
    <li>
      <a href="#comenzando">Comenzando</a>
      <ul>
        <li><a href="#prerequisitos">Prerequisitos</a></li>
        <li><a href="#instalación">Instalación</a></li>
      </ul>
    </li>
    <li><a href="#contribuyendo">Contribuyendo</a></li>
    <li><a href="#licencia">Licencia</a></li>
    <li><a href="#contacto">Contacto</a></li>
  </ol>

<!-- ABOUT THE PROJECT -->

## Introduccion

El proyecto TRAVELGENIE, consiste en un sistema de Inteligencia Artificial diseñado para asistir en la planificación de viajes alrededor del mundo. Utilizando técnicas avanzadas de generación de prompts, TravelGenie crea itinerarios de viaje detallados y personalizados para diversos destinos y actividades, proporcionando recomendaciones útiles y visuales.
<p align="right">(<a href="#tabla-de-contenidos">volver</a>)</p>

### Construido con

![Static Badge](https://img.shields.io/badge/Python-green?style=for-the-badge) como lenguaje de programación que cuenta con una amplia gama de librerías y frameworks que facilitan la interacción con APIs y el procesamiento de datos. Librerías como openai están bien documentadas y simplifican enormemente la implementación de solicitudes API.

![Static Badge](https://img.shields.io/badge/APIOpenAI-blue?style=for-the-badge) como API proveedora de modelos de inteligencia artificial desarrollado por OpenAI. Cada modelo de OpenAI, puede considerarse como una funcionalidad o capacidad específica. Estos modelos son entrenados para realizar diversas tareas relacionadas con el procesamiento del lenguaje natural. Pueden llevar a cabo funciones como generación de texto, imágenes, traducción de idiomas, respuestas a preguntas, redacción de contenido, etc., todo basado en el contexto proporcionado durante su entrenamiento.

<p align="right">(<a href="#tabla-de-contenidos">volver</a>)</p>

### Descripción general

TravelGenie resuelve la problemática de la planificación de viajes al proporcionar itinerarios detallados basados en los destinos y actividades especificados por el usuario. Utiliza modelos de IA para generar tanto texto descriptivo como imágenes que ayudan a visualizar los planes de viaje.

#### Entregable

El proyecto entrega una aplicación web interactiva donde los usuarios pueden ingresar sus destinos y actividades, y recibir itinerarios de viaje personalizados con imágenes representativas.

Los entregables son:

- Páginas HTML
- Código fuente en archivos Python.
- [Readme.md](https://https://github.com/hmfarias/TravelGenie/edit/main/readme.md) con instrucciones de uso.


<p align="right">(<a href="#tabla-de-contenidos">volver</a>)</p>

#### Uso de Librerías

- **openAI:** Para interactuar con las API de GPT-3 y DALL-E.


<p align="right">(<a href="#tabla-de-contenidos">volver</a>)</p>

<!-- GETTING STARTED -->

## Comenzando

Esta guía describe paso a paso cómo utilizar el sitio web de TRAVELGENIE.

### Prerequisitos

Antes de comenzar la instalación, es necesario:

- Python 3.8 o superior
- Cuenta de OpenAI con acceso a las API de GPT-3 y DALL-E
- Pip (gestor de paquetes de Python)
- API Key de API openAI

### Instalación 
(en caso de que se opte por bajar el proyecto a una ubicación local)

1. ##### Clonar el proyecto del repositorio

- Cree una carpeta en un directorio local y desde la `terminal` dentro de la carpeta creada, inicialice git:

```
git init
```

- Clonar todo el proyecto:

```
git clone https://github.com/hmfarias/TravelGenie.git
```

- Crea un entorno virtual:
```
  python -m venv env
  source env/bin/activate  # En Windows usa `env\Scripts\activate`
```

- Instala las dependencias:
```
pip install openai==0.28 (mejorar el request)
pip install jupyter notebook (instalar tanto jupyter como notebook, para poder crear nuestro servidor local)
pip install "..." seguido de la dependencia necesaria para nuestro proyecto o modelo.

Una vez instaladas las dependencias, debemos ejecutar nuestro entorno jupyter notebook con el comando jupyter notebook
```

    
<!-- CONTRIBUTING -->

## Contribuyendo

Las contribuciones son lo que hace que la comunidad de código abierto sea un lugar increíble para aprender, inspirar y crear. Cualquier contribución que haga es **muy apreciada**.

Si tiene una sugerencia para mejorar este proyecto, por favor haga un "fork" al repositorio y cree un "pull request". También puede simplemente abrir un "issue" con la etiqueta "mejora".
¡No olvide darle una estrella al proyecto! ¡Gracias de nuevo!

1. Fork al Proyecto
2. Cree una nueva rama para su característica (`git checkout -b feature/newFeature`)
3. Commit para los cambios (`git commit -m 'Add some newFeature'`)
4. Push a la nueva rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

<p align="right">(<a href="#tabla-de-contenidos">volver</a>)</p>

<!-- LICENSE -->

## Licencia

Distribuido bajo la licencia MIT. Consulte `LICENSE.txt` para obtener más información.

<p align="right">(<a href="#tabla-de-contenidos">volver</a>)</p>

<!-- CONTACT -->

## Contacto

Marcelo Farias - [+54 9 3512601888] - hmfarias7@gmail.com

Link del Proyecto: [https://https://github.com/hmfarias/TravelGenie](https://https://github.com/hmfarias/TravelGenie)

<p align="right">(<a href="#tabla-de-contenidos">volver</a>)</p>

<!-- ACKNOWLEDGMENTS -->

<!-- MARKDOWN LINKS & IMAGES -->

<!-- [statuss-shield]: https://img.shields.io/badge/STATUS-Developing-green -->

[statuss-shield]: https://img.shields.io/badge/STATUSS-finished-green
[statuss-url]: https://https://github.com/hmfarias/TravelGenie#readme
[forks-shield]: https://img.shields.io/github/forks/hmfarias/TravelGenie
[forks-url]: https://github.com/hmfarias/TravelGenie/network/members
[stars-shield]: https://img.shields.io/github/stars/hmfarias/TravelGenie
[stars-url]: https://github.com/hmfarias/TravelGenie/stargazers
[issues-shield]: https://img.shields.io/github/issues/hmfarias/TravelGenie
[issues-url]: https://github.com/hmfarias/TravelGenie/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg
[license-url]: https://github.com/hmfarias/TravelGenie/blob/master/LICENSE.txt
[product-screenshot]: https://github.com/hmfarias/TravelGenie/blob/main/assets/images/screenShot.webp
[product-screenshot-navbar]: https://github.com/hmfarias/TravelGenie/blob/main/assets/images/navbar.webp
[others-url]: https://github.com/hmfarias/TravelGenie





