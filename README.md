<!-- @format -->

<div>
<img align="right" width="100%"  src="https://cdn.buymeacoffee.com/uploads/cover_images/2024/01/ONqPaQ0vktYLqvnFB0TsMapLxTfOzxvKuEvvCgNv.png@1950w_0e.webp" />
</div>

<div align="center">

  <h1>Instagram Bot - Bot para Instagram</h1>
  <a href='https://www.instagram.com/danielmena.foto' target="_blank"><img alt='Instagram' src='https://img.shields.io/badge/Instagram-100000?style=flat-square&logo=Instagram&logoColor=white&labelColor=F70797&color=F70797'/></a> <a href='https://www.youtube.com/@codeffee_' target="_blank"><img alt='Youtube' src='https://img.shields.io/badge/Youtube-100000?style=flat-square&logo=Youtube&logoColor=white&labelColor=D30202&color=D30202'/></a> <a href='https://www.buymeacoffee.com/codeffee' target="_blank"><img alt='buy me a coffee' src='https://img.shields.io/badge/Buy_Me a Coffee-100000?style=flat-square&logo=buy me a coffee&logoColor=080000&labelColor=F7C602&color=F7C602'/></a>

<sub>Creador: <a href="https://www.instagram.com/danielmena.foto" target="_blank">Daniel Mena</a><br>
<small> Enero, 2024</small></sub>

</div>

---

- [Introduction](#introducción)
- [Requirements](#requirements)
- [How to Use Repo](#how-to-use-repo)
  - [Star and Fork this Repo](#star-and-fork-this-repo)
  - [Clone your Fork](#clone-your-fork)
  - [Create a New Branch](#create-a-new-branch)
  - [Structure Exercise Solutions](#structure-exercise-solutions)
  - [Commit Exercise Solutions](#commit-exercise-solutions)
  - [Update your Fork Daily](#update-your-fork-daily)
- [Setup](#setup)
  - [Install Node.js](#install-nodejs)
  - [Browser](#browser)
    - [Installing Google Chrome](#installing-google-chrome)
    - [Opening Google Chrome Console](#opening-google-chrome-console)
    - [Writing Code on Browser Console](#writing-code-on-browser-console)
      - [Console.log](#consolelog)
      - [Console.log with Multiple Arguments](#consolelog-with-multiple-arguments)
      - [Comments](#comments)
      - [Syntax](#syntax)
    - [Arithmetics](#arithmetics)
  - [Code Editor](#code-editor) - [Installing Visual Studio Code](#installing-visual-studio-code) - [How to Use Visual Studio Code](#how-to-use-visual-studio-code)
  <br>
  <p align="center">🧡 <strong>¿Esta App fué de Ayuda?</strong> 🧡<br>
  <small align="center">Gracias por tu <strong>apoyo</strong>, me ayuda a seguir adelante desarrollando más herramientas para automatizar tu trabajo.</small></p>
  <p align="center"><a href='https://www.buymeacoffee.com/codeffee' target="_blank"><img alt='buy me a coffee' src='https://img.shields.io/badge/Buy_Me a Coffee-100000?style=for-the-badge&logo=buy me a coffee&logoColor=080000&labelColor=F7C602&color=F7C602'/></a></p>

---

## Creador y Programador de Publicaciones para Instagram

Este software fué creado para programar las pubicaciones que se realizan en una cuenta que comparte frases motivacionales o frases de cualquier tipo en Instagram.

No se encarga sólamente de programar las publicaciones sino también de crearlas, el software crea una imagen a partir de una plantilla en imagen y agrega el texto al centro de la imagen y la publica a la hora indicada.

Al momento de crear la imagen a publicar el software elige una frase al azar de una base de datos de frases que podemos editar y que no tiene un límite de frases.

A continuación te mostraré el funcionamiento este software.

![frases-para-instagram](https://smartwebtutoriales.com/github/frases-para-instagram-bot.png)

## Aclaraciones

¡¡ ACLARACIÓN !!
Este software NO requiere que ingreses tus credenciales de instagram (usuario o contraseña) para funcionar, trabaja usando el servicio oficial de Facebook (Instagram API), eso garantiza que tu cuenta NO será bloqueada por Instagram al usar este bot como sucede con otros bots de internet.

## ¡No ingresarás tu contraseña!

La mayoría de bots que encontrarás en internet se conectan a tu cuenta de Instagram usando directamente tus credenciales, esto quiere decir que debes darle al bot tu usuario y contraseña, pero ese NO es el caso de este software.

Otro problema con los demás bots es que Instagram detecta actividad inusual en tu cuenta y procede a bloquear tu cuenta por tiempo indefinido porque Instagram no aprueba el uso de bots que no se conecten por medio de la API oficial de Facebook.

El software que te presento en este repositorio usa la API de Facebook para conectarse a tu cuenta de Instagram, la API es el canal oficia habilitado por Facebook para que puedas usar sus productos desde programas externos, y es por eso que tu cuenta jamás se verá afectada por el uso de este software y tampoco deberás proveer las credenciales de tu cuenta.

La única restricción que pone la API de Facebook es que no podemos pasar de 50 publicaciones diaras a través de la API, pero seamos sinceros, difícilmente llegaremos a esa cifra 😁

![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white) ![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)

## Configuración del Bot

La configuración consiste en 4 pasos:

1. Prepara tu cuenta para conectarla a la API
2. Vincular tu cuenta de Instagram con una página de Facebook
3. Crear una cuenta en ImgBB (gratis)
4. Configurar la API
5. Aplicar las API keys al software

```bash
mkdir -p solutions/day-01 # `-p` helps create nested directories
touch solutions/day-01/level1.js # touch creates a file
```

## Sobre el desarrollo del Software

Este software fue desarrollado en su totalidad usando Python en su versión 3.11.4 en Visual Studio Code.
Para crear la interfaz de usuario se utilizó la librería de Python CustomTkinter.
Para crear el archivo ejecutable (.EXE) partiendo de Python se usó la librería Pyinstaller.
Se utilizó Chat GPT únicamente para generar las frases de ejemplo que contiene el archivo frases.json.

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white) ![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)

🎉 CONGRATULATIONS ! 🎉
