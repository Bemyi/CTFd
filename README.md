
# ![](https://github.com/CTFd/CTFd/blob/master/CTFd/themes/core/static/img/logo.png?raw=true)

## Qué es CTFd?

CTFd es una herramienta desarrollada específicamente para la organización y ejecución de competiciones de CTF. Proporciona una interfaz fácil de usar que permite al administrador crear, administrar y distribuir desafíos de manera efectiva.

![CTFd is a CTF in a can.](https://github.com/CTFd/CTFd/blob/master/CTFd/themes/core/static/img/scoreboard.png?raw=true)

## Adaptación "CTF en escuelas secundarias"
Esta adaptación presenta una nueva versión de la herramienta *CTFd* orientada a la organización y gestión de competencias de ciberseguridad en las escuelas, promoviendo la autonomía y participación de los equipos escolares. Para ello se ofrecen nuevas funcionalidades.
- **Automatización de la carga de desafíos:** facilitando la carga masiva y organizada de desafíos por categoría de contenido y nivel de dificultad, mediante un script en Python que integra la herramienta ctfcli (ofrecida por CTFd).
- **Unirse a equipos:** se buscó simplificar la incorporación de estudiantes a equipos de la competencia sin necesidad de recordar el nombre del equipo, mediante un acceso directo en la tabla de equipos.
- **Rol Autor:** para poder cargar y gestionar desafíos sin necesidad de contar con privilegios administrativos en la plataforma, mediante un nuevo rol que cuenta con permisos específicos de acceso.
- **Repositorio base de desafíos:** para disponer de un punto de partida sobre contenidos de seguridad informática para facilitar la creación de la competencia en las escuelas. Esto Mediante un acceso a un [repositorio público en GitHub](https://github.com/Bemyi/ctfd-challenges/).
- **Documentación:** Disponer de documentación simple sobre la configuración de la plataforma.

## Instalación

Prerrequisitos:

 - La PC debe contar con [Docker](https://www.docker.com/) instalado.
 - Preferentemente utilizar sistema operativo Linux.
 - Tener instalado [Python 3](https://www.python.org/downloads/) >= 3.10.
 - Tener instalado [pip](https://pypi.org/project/pip/).

Una vez clonado el repositorio, nos colocamos en el directorio raíz de la plataforma y ejecutamos el siguiente comando:

`docker-compose up`

Para continuar con la instalación te recomendamos seguir la guía realizada para instanciación de [CTF en escuelas secundarias](https://docs.google.com/document/d/1tBe47xcGkL5nekVN6Vl18kCik0Pmn6ZIODSYpaBsLFQ/edit?tab=t.0#heading=h.yq18kulgr7bh).
