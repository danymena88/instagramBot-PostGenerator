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

- [Intro y Funcionamiento](#Creador-y-Programador-de-Publicaciones-para-Instagram)
- [Aclaración](#aclaraciones-❗❗❗)
- [No necesita contraseña](#¡No-ingresaras-tu-contraseña!-💛)
- [Configuración](#Configuracion-del-Bot-para-Instagram-🤖)
- [Desarrollo del Software](#Sobre-el-desarrollo-del-Software-💻)

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

![frases-para-instagram](https://smartwebtutoriales.com/github/frases-para-instagram-bot-2.png)
<br><br>
Funcionamiento
<br>

1. El programa tiene 3 paneles para programar publicaciones pero puedes programar más de 3 publicaciones en diferentes dias y horas. Por ejemplo en el campo "Día" puedes colocar del cero al seis donde cero es igual a lunes y seis es igual a domingo pero puedes colocar un rango de 0-2 que significa de lunes a miércoles. De la misma forma se puede usar para los campos "Hora" y "Minuto". Si colocas el símbolo "\*" significa "Todos los dias, o lo que es igual a: de lunes a domingo".

2. Después de programar las publicaciones das clic en "Guardar" y abajo del botón podrás ver la información de las tareas programadas.

3. En este campo puede colocar el caption o el copy de la publicación, puedes colocar hashtags o texto simple.

4. Después de colocar el caption de la publicación das clic en "Guardar Texto" para que el texto quede guardado (a pesar que cierres la app) y pueda usarse en otras publicaciones programadas. El botón "Publicar" es para publicar inmediatamente y no esperar hasta la hora programada.

5. En la barra lateral encontrarás el logo de la marca que he creado para las herramientas que desarrollo y puedes darle clic para ver más información. También verás algunas instrucciones para tener siempre presente el formato que debes utilizar, y el boton de "Tema" es para elegir entre el tema oscuro o claro.
   <br>

## Aclaración ❗❗❗

¡¡ ACLARACIÓN !!
Este software NO requiere que ingreses tus credenciales de instagram (usuario o contraseña) para funcionar, trabaja usando el servicio oficial de Facebook (Instagram API), eso garantiza que tu cuenta NO será bloqueada por Instagram al usar este bot como sucede con otros bots de internet.

## ¡No ingresarás tu contraseña! 💛

La mayoría de bots que encontrarás en internet se conectan a tu cuenta de Instagram usando directamente tus credenciales, esto quiere decir que debes darle al bot tu usuario y contraseña, pero ese NO es el caso de este software.

Otro problema con los demás bots es que Instagram detecta actividad inusual en tu cuenta y procede a bloquear tu cuenta por tiempo indefinido porque Instagram no aprueba el uso de bots que no se conecten por medio de la API oficial de Facebook.

El software que te presento en este repositorio usa la API de Facebook para conectarse a tu cuenta de Instagram, la API es el canal oficia habilitado por Facebook para que puedas usar sus productos desde programas externos, y es por eso que tu cuenta jamás se verá afectada por el uso de este software y tampoco deberás proveer las credenciales de tu cuenta.

La única restricción que pone la API de Facebook es que no podemos pasar de 50 publicaciones diaras a través de la API, pero seamos sinceros, difícilmente llegaremos a esa cifra 😁

![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white) ![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)

## Configuración del Bot para Instagram 🤖

La configuración consiste en 4 pasos:

1. Prepara tu cuenta para conectarla a la API
2. Vincular tu cuenta de Instagram con una página de Facebook
3. Crear una cuenta en ImgBB (gratis)
4. Configurar la API
5. Aplicar las API keys al software

## Sobre el desarrollo del Software 💻

Este software fue desarrollado en su totalidad usando Python en su versión 3.11.4 en Visual Studio Code.
Para crear la interfaz de usuario se utilizó la librería de Python CustomTkinter.
Para crear el archivo ejecutable (.EXE) partiendo de Python se usó la librería Pyinstaller.
Se utilizó Chat GPT únicamente para generar las frases de ejemplo que contiene el archivo frases.json.

Otras librerías utilizadas:

```bash
APScheduler               3.10.1
imgbbpy                   0.1.3
Pillow                    9.5.0
pystray                   0.19.4
requests                  2.26.0
```

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white) ![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)

🎉 CONGRATULATIONS ! 🎉
