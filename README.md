Paulina H Un formulario donde los usuarios puedan ingresar la información de la reparación (nombre del cliente, tipo de reparación, descripción).

Carlos Una sección donde se muestren los servicios que ofrecen y sus precios.

Eduardo Un sistema para programar citas para las reparaciones.

Paulina R Un área para realizar el pago en línea.

Jasmin Dar el marco general HTML

Leonardo README
----------------------------------------------------------------------------------
# estructura de los ficheros 

### autofix/
│
├── 📂 assets/
│   ├── 📂 css/
│   │   └── styles.css
│   ├── 📂 js/
│   │   └── main.js
│   └── 📂 images/
│       ├── logo.png
│       └── icon-oil.svg
│
├── 📄 index.html
├── 📄 servicios.html
├── 📄 citas.html
├── 📄 pagos.html
├── 📄 formularios.html
└── 📄 README.md

----------------------------------------------------------------------------------

# Proyecto AutoFix 🚗💨

¡Bienvenido al repositorio oficial del proyecto AutoFix! Aquí gestionamos todo el código fuente y la colaboración para crear la página web de nuestro servicio de reparación de vehículos a domicilio.

## Descripción General

AutoFix nació para modernizar la forma en que nuestros clientes solicitan reparaciones de vehículos. Dejamos atrás la libreta y el teléfono para dar el salto a una solución digital que nos permita ser más eficientes y ofrecer un mejor servicio.

Este proyecto consiste en la creación de una página web de varias vistas donde los usuarios pueden:
-   Conocer los servicios que ofrecemos y sus precios.
-   Solicitar una reparación llenando un formulario simple.
-   Agendar una fecha para la visita de nuestro técnico.
-   Realizar una simulación de pago en línea de forma segura.

El objetivo es tener una plataforma centralizada, intuitiva y profesional que refleje la calidad de nuestro trabajo.

## Características Principales

* **Visualización de Servicios:** Una sección clara y directa con nuestros servicios estrella y sus precios.
* **Formulario de Solicitud Unificado:** Todos los pasos, desde la solicitud hasta el pago, están en un solo lugar para facilitar el proceso al cliente.
* **Agendamiento de Citas:** Un selector de fecha integrado en el formulario.
* **Diseño Limpio y Responsivo:** La página está diseñada para verse bien y ser funcional tanto en computadores de escritorio como en dispositivos móviles.

---

## Mini Tutorial de Colaboración con Git

Para mantener el orden y trabajar en equipo de manera eficiente, seguimos un flujo de trabajo basado en Git y GitHub. Si eres nuevo en el equipo, sigue estos pasos para empezar a colaborar.

### Prerrequisitos

Asegúrate de tener instalado [Git](https://git-scm.com/downloads) en tu computadora.

------------------------------------------------------------------------------------

# Guía Rápida de Git y GitHub para Principiantes
Sigue estos pasos en orden para tener todo listo y empezar a contribuir.

### Fase 1: Configuración Inicial (Solo se hace una vez)
## Paso 1: Instalar Git en tu computadora

Si aún no lo tienes, descarga e instala Git desde su página oficial. Es un programa gratuito.

➡️ Descargar Git

Durante la instalación, puedes dejar todas las opciones por defecto.

## Paso 2: Presentarte ante Git

Abre tu terminal (o "Git Bash" si estás en Windows) y preséntate. Git usará esta información para firmar cada cambio que hagas.

Reemplaza "Tu Nombre" con tu nombre real
git config --global user.name "Tu Nombre"

Reemplaza "tu.email@example.com" con tu email (el mismo que usas en GitHub)
git config --global user.email "tu.email@example.com"

## Paso 3: Clonar el Repositorio (Traer el proyecto a tu PC)

"Clonar" significa crear una copia local del proyecto que está en GitHub.

Ve a la página principal de nuestro repositorio en GitHub.

Haz clic en el botón verde que dice < > Code.

Copia la URL que aparece en la pestaña HTTPS.

En tu terminal, navega a la carpeta donde guardas tus proyectos (ej: cd Documents/Proyectos) y ejecuta el siguiente comando:

Pega la URL que copiaste de GitHub
git clone https://github.com/AliceV66/AutoFix_grupo3.git

Ahora, entra a la carpeta que se acaba de crear:

Reemplaza "AutoFix_grupo3" con el nombre exacto de la carpeta
cd AutoFix_grupo3

¡Felicidades! Ya tienes el proyecto en tu computadora.

### Fase 2: El Ciclo de Trabajo (Lo que harás cada día)
Imagina que tu tarea es añadir una nueva sección de "Testimonios" a la página. Este es el proceso que seguirías:

## Paso 4: Sincronizar tu Repositorio Local

¡Este es el paso más importante! Antes de empezar a escribir una sola línea de código, asegúrate de tener la versión más reciente del proyecto para evitar conflictos con los cambios de tus compañeros.

1. Asegúrate de estar en la rama principal
git checkout main

2. Descarga todos los cambios de GitHub a tu PC
git pull origin main

## Paso 5: Crear una Rama (Tu espacio de trabajo seguro)

Una "rama" (branch) es como una copia del proyecto donde puedes hacer cambios de forma segura sin afectar la versión principal (main).

Crea una nueva rama y muévete a ella. Nómbrala según la tarea que vas a realizar.
git checkout -b feature/seccion-testimonios

Tip: Nombra tus ramas de forma descriptiva. Usa feature/ para nuevas funcionalidades y fix/ para corregir errores.

## Paso 6: ¡A programar! (La parte divertida)

Abre la carpeta del proyecto en tu editor de código (como Visual Studio Code) y haz todos los cambios necesarios en los archivos index.html , estilos.css , etc. Para crear la nueva sección de testimonios.

## Paso 7: Revisar y Preparar tus Cambios

Una vez que hayas hecho algunos avances, es hora de decirle a Git qué cambios quieres guardar.

1. Revisa qué archivos has modificado (este comando es solo para ver, no cambia nada)
git status

2. Agrega los archivos que quieres guardar al "área de preparación" (staging area).
El punto "." significa "todos los archivos que he modificado".
git add .

## Paso 8: Guardar tus Cambios (Hacer un "Commit")

Un "commit" es como un punto de guardado permanente en tu máquina. Cada commit debe tener un mensaje que describa qué hiciste.

Guarda los archivos que preparaste en el paso anterior con un mensaje descriptivo
git commit -m "feat: Añade la sección de testimonios en la página principal"

## Paso 9: Subir tu Rama a GitHub

Ahora, envía tu rama (con todos los commits que hiciste) desde tu computadora a GitHub para que el equipo pueda ver tu trabajo.

Reemplaza "feature/seccion-testimonios" con el nombre de tu rama
git push origin feature/seccion-testimonios

## Paso 10: Crear un "Pull Request" (Proponer tus cambios)

El último paso se hace en la página de GitHub. Un "Pull Request" (PR) es una solicitud formal para que tus cambios se incorporen a la rama principal (main).

Ve a la página del repositorio en GitHub.

Verás una notificación amarilla con el nombre de tu rama. Haz clic en el botón verde "Compare & pull request".

Ponle un título claro a tu PR (ej: "Implementación de la Sección de Testimonios").

En la descripción, explica brevemente qué hiciste y por qué.

En la sección "Reviewers" (Revisores) a la derecha, selecciona a uno o más compañeros para que revisen tu código.

Haz clic en "Create pull request".