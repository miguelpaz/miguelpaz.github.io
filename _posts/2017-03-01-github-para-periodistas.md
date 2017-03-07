---
layout: post
title: Github para Periodistas
tags:
- Courses
- Tutorials
- Español
---

Por Miguel Paz

En este tutorial aprenderás los rudimentos básicos para usar Github para crear tu sitio web, para administrar desde tu computador tus proyectos de sitios web usando Github Desktop y a publicarlos en la web. También aprenderás la jerga de Github, necesaria para entender sus herramientas de administración y publicación.

## 1. Crea tu cuenta en Github

Como ya dijimos [Github](https://www.github.com/) es el equivalente a un Dropbox para proyectos de código, datos y web. Permite mantener una versión de tu proyecto en tu computador (local) y otra en Github (en sus servidores: "la nube") para sincronizar cambios y mantener un registro de todos los cambios del proyecto. Así si te equivocas **puedes volver atrás**. Github está construido sobre [Git,](http://git-scm.com/) un sistema de control de versiones usado por programadores. Pero como es un poco complicado al principio, iremos por el camino fácil.

Ok. Partamos.

Anda a [Github](https://www.github.com/) y crea tu nombre de usuario y pasword. Usa un nombre fácil de recordar, en minúsculas y sin espacios. Algo como **juanperez**. Nada de **JuAn32pEreZ1. Prohibido.**  

![Github homepage][1]

[1]: assets/images/github-homepage.png

## 2. Crea tu primer repositorio

Una vez registrado verás una pantalla igual o similar a la que se ve acá abajo. Busca el botón **"New repository"** y púlsalo para crear tu primer **repositorio**. Como dijimos, Github usa su propio *lingo* para nombrar las cosas. **Repositorio es igual a proyecto o a carpeta** (dentro de la cual tendrás los archivos y más carpetas de tu proyecto). Más adelante veremos como acceder y guardar otros proyectos, **clonándolos** (copiándolos) o haciendo un **fork** (algo así como tomar un pedazo de carne con un tenedor y llevarlo a nuestra plato). ¿Ya pulsaste en "New repository"?

![Github homepage][2]

[2]: assets/images/github-homepage-1.png

## 3. Nombra tu repositorio

- Nombra tu repositorio en minúsculas, sin espacios ni símbolos extraños.
- Incluye una descripción breve.
- Define si el repositorio será público o privado.
- Haz check en la caja de "Initialize this repository with a README"
- Ahora podrás pulsar el botón “Create repository”.

![][3]

[3]: assets/images/3-nombra-tu-repositorio.png

## ¡Voilá! Ya tienes tu primer repositorio

Lo vas a copiar a tu computador. Antes, anda a tu computador y lee el siguiente paso.

![][4]

[4]: assets/images/-iexcl-voil-aacute---ya-tienes-tu-primer-repositorio-.png

## 4. Crea una carpeta donde guardarás todos tus repositorios

Realizar proyectos digitales requiere que seas ordenado y definas dónde guardarás este y otros proyectos. En mi caso, tengo una carpeta madre en la cual guardo todos los repositorios de clases y otros proyectos. La llamo para no olvidarme: **repos.**

- Crea tu carpeta **repos** así todos sabremos siempre dónde tienes tus repositorios y no lo olvidarás
- Cuando copies tu repositorio desde Github a tu computador, guarda el repositorio dentro de **repos.**

![][5]

[5]: assets/images/4-crea-una-carpeta-d-oacute-nde-guardar-aacute-s-todos-tus-repositorios.png

## 5. Instalar Github Desktop en tu computador

¿Recuerdas cuando aprendiste a usar una aplicación de subida de archivos a servidor vía FTP como [File Zilla](https://filezilla-project.org/) para publicar tu sitio web?

Bueno [Github Desktop](https://desktop.github.com/) sirve el mismo propósito en Github. Es la herramienta más rápida y fácil de comenzar a trabajar con repositorios para subirlos y bajarlos de los servidores de Github.

- Descarga [Github Desktop](https://desktop.github.com/) e instálalo. Muévelo a tu carpeta de Aplicaciones o Applications.
- Haz click sobre el ícono de Github Desktop (el [octogato](https://octodex.github.com/)) y cuando se abra la aplicación, anda al menú superior izquierdo y pulsa sobre Preferencias o **Preferences**.

*Si tienes dudas, más adelante revisa las [guías de ayuda](https://help.github.com/desktop/) de la aplicación.*

![][6]

[6]: assets/images/5-instalar-github-desktop-en-tu-computador.png

## 6. Agrega tu nombre de usuario y contraseña

- En la ventana de **Preferences** selecciona **Accounts**.
- Ingresa tu nombre de usuario en login y tu contraseña y haz click en **Sign In**.  
- Ya estás adentro.

![][7]

[7]: assets/images/6-agrega-tu-nombre-de-usuario-y-contrase-ntilde-a.png

## 7. Clona (copia) tu repositorio a tu computador con Github Desktop

- En la barra lateral izquierda de Github Desktop debieras ver en la lista de repositorios el repositorio que creaste.
- Si no lo ves, como es mi caso, sigue los pasos que se ven en la imagen de abajo y haz click en "Clone micasa"

*Si tienes dudas, más adelante revisa las *[*guías de ayuda*](https://help.github.com/desktop/)* de la aplicación.*

![][8]

[8]: assets/images/7-clona--copia--tu-repositorio-a-tu-computador-con-github-desktop.png

## 8. Guarda el repositorio clonado en tu carpeta repos

Al **clonar** y guardar el repositorio en tu carpeta madre repos lo que estás haciendo es **bajar a tu computador una copia de tu repositorio** que estaba alojado en Github.com.

![][9]

[9]: assets/images/8-guarda-el-repositorio-clonado-en-tu-carpeta-repos.png

## 9. Tu primer repositorio y tu primer "Commit"

Git y Github llevan un registro de todos los cambios que haces en tu repositorio (editaste texto, agregaste una foto, etc).

El objetivo es que tu puedas conocer e identificar todos los cambios importantes que hagas y tener a mano las distintas versiones. Algo así como llevar un registro de cambios de todos los borradores que escribes hasta que tu reportaje es publicado.

Peeeero... para que te sea fácil identificar los cambios debes contarle a Github que los hiciste y publicarlos. Esto se llama "Commit changes" ("cometer cambios" o hacer cambios). En corto "Commit".

La regla de oro es que hagas commits muy frecuentemente y que expliques brevemente qué cambios hiciste.


![][10]

[10]: assets/images/9-tu-primer-repositorio-y-tu-primer--commit-.png

## 10. Crea un index.html, haz tu segundo "Commit" y súbelo a Github

Reitero: La regla de oro es que hagas commits muy frecuentemente y que expliques brevemente qué cambios hiciste.

- Abre tu repositorio en Sublime, escribe un mensaje tipo (el que quieras), guarda el archivo como index.html dentro del repositorio (carpeta).
- Anda a Github Desktop y revisa la parte superior de Commited o Uncommited Changes. ¿Qué ves?
- Haz tu segundo commit.

![][11]

[11]: assets/images/10-crea-un-indexhtml--haz-tu-segundo--commit--y-s-uacute-belo-a-github.png

## 11. Resultado


![][12]

[12]: assets/images/11-resultado.png

## Ejercicios para aplicar lo aprendido

### 1. Crea tu primer sitio web personal en Github

- Ir a [https://pages.github.com/](https://pages.github.com/)
- Haz click en [User or organization site](https://pages.github.com/#user-site)
- Anda a [GitHub](https://github.com/) y [crea un nuevo repositorio](https://github.com/new) que se llame **username.github.io**, donde *username* es tu tu nombre de usuario en Github.

*Si tienes dudas más adelante revisa las *[*guías de ayuda*](https://help.github.com/desktop/)* de la aplicación.*

![][13]

[13]: assets/images/ejercicio-1--crear-tu-primer-sitio-web-personal-en-github.png

## Clónalo a tu computador

![][14]

[14]: assets/images/cl-oacute-nalo-a-tu-computador.png

## Debiera verse así

![][15]

[15]: assets/images/debiera-verse-as-iacute-.png

### 2. Crea una página web y súbela a tu repositorio tunombredeusuario.github.io haciendo "Commit"

Incluye:

* Index.html
* Carpeta de archivos de imágenes y dentro, las imágenes.
* Carpeta de archivos de css y dentro, el o los archivos .css

****Ojo: ****Puedes usar una página web que ya hayas hecho.*

1. Copia los archivos (Index.html y las carpetas de imágenes y de css) y pégalos dentro de la carpeta o repositorio **tunombredeusuario.github.io** en tu computador.
1. Recuerda: la carpeta o repositorio **tunombredeusuario.github.com **está dentro de la carpeta madre **repos.** que ya creaste.
1. Ahora abre en Github Desktop la carpeta o repositorio **tunombredeusuario.github.com **y haz un **commit** detallando los cambios.

- Resultado: Esta es la página que estás leyendo ahora mismo [https://miguelpaz.github.io/](https://miguelpaz.github.io)


## 3. Haz un "fork"

1. Lee y revisa el ensayo ["What is Code"](https://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/) de Paul Ford en Bloomberg. Ford escribió el texto y cada línea de código con la que construyó la página web del artículo. ¿Te gustaría saber la estructura del código y verlo con tus propios ojos? Visita el [repositorio del artículo que el autor publicó en Github](https://github.com/BloombergMedia/whatiscode) con un objetivo más bien educacional.
2. Pulsa el botón **Fork** ubicado en la parte superior derecha de la página del repositorio. Hacer un Fork significa crear una **copia** de un proyecto de otra persona u organización en tu Github. En este caso haces fork de [https://github.com/BloombergMedia/whatiscode](https://github.com/BloombergMedia/whatiscode) y se crear'a la copia del repositorio en tu cuenta **github.com/tunombredeusuario**.
3. Verás la copia en **github.com/tunombredeusuario/whatiscode**
4. Pulsa el botón verde Clone or download y luego haz click en **Open in Desktop**.
5. Guarda el repositorio en tu carpeta **repos**
6. Abre el repositorio con tu editor de texto de preferencia (Sublime, Atom, etc.) y abre el index.html, haz los cambios que quieras, guárdalos y luego abre Github Desktop, selecciona ese repositorio y haz commit para que se publiquen los cambios en el repositorio online en Github.
7. Fork te permite trabajar en un proyecto sin afectar el proyecto original. Luego, si le hiciste mejoras al proyecto y quieres compartirlas con su autor original, puedes hacer un "Pull request" que, dicho en simple, es un aviso al autor original de que hiciste cambios, cuáles fueron y que están disponibles para que él o ella los acepten e integren al repositorio original.

> **Tip:** Bucea por esta [lista de medios recomendados en Github](https://github.com/showcases/open-journalism) y clona los repositorios que te dan curiosidad y revísalos por dentro.

---
*Parte del material del curso Craft 2 en Español del Programa Bilingüe de la Maestría de Periodismo de CUNY*
