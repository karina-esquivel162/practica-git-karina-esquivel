# *Karina Sarahi Esquivel George*
**Matrícula:** *2630162*

**Nombre de la práctica:** Creación y sicronización de repositorios con Git y GitHub.

**Objetivo de la práctica:** Aprender como hacer repositorios en git y github, como modificarlos y practicar los comandos.

**Procedimiento realizado:** Se creó una carpeta llamada practica_git_karina_esquivel y dentro de ella se inicializó un repositorio con git init. Luego se renombró la rama principal a main, se añadieron los archivos README.md y datos.txt, y se registraron con un primer commit.

Después se creó un repositorio en GitHub con el mismo nombre y se vinculó al local mediante git remote add origin. Con git push -u origin main se enviaron los archivos a GitHub.

Después se editó el archivo datos.txt directamente en GitHub y se descargaron los cambios al repositorio local con git pull. Finalmente, se hicieron nuevas modificaciones desde la computadora, se confirmaron con git commit y se enviaron otra vez con git push.

**Comandos de git utilizados**
1. git config --global user.name, user.email
2. git init
3. git branch -M main
4. git status
5. git add -A
6. git commit -m "texto"
7. git remote add origin URL_DEL_REPOSITORIO
8. git remote -v
9. git push -u origin main
10. git pull origin main

**Explicación de los comandos**
1. Sirve para configurar git con nuestros datos.
2. Crea un repositorio de Git nuevo y vacío en el directorio actual.
3. Configurar la rama principal con el nombre main.
4. Ver el estado del repositorio.
5. Agregar los archivos al área de prepación (Staging Area)
6. Guarda una foto de los archivos listos en el repositorio local.
7. Vincula el repositorio local con el repositorio remoto.
8. Verifica que el repositorio remoto se haya agregado correctamente.
9. Envia por primera vez el repositorio local a GitHub.
10. Descarga los cambios realizados en GitHub.

**Como se creo el repositorio local:**
El repositorio local se creó mediante el comando git init.
Después se configuró la rama principal como main.
Despues se crearon los archivos README.md y datos.txt

**Como se vinculó el repositorio local con GitHub:**
Se creó un repositorio público en GitHub con el mismo nombre que
el repositorio local de la terminal. Después se utilizaron los códigos nescesarios para establecer conexión entre el repositorio local y el repositorio de GitHub.

**Sincronización Local - GitHub:**
Se realizó un commit en el repositorio
local y posteriormente se utilizó git push. Asi los archivos y cambios realizados localmente fueron enviados al
repositorio de GitHub.

**Sincronización GitHub - Local:**
Para comprobar se modificó el archivo
datos.txt directamente desde GitHub. Después se utilizó el
comando git pull origin main desde PowerShell para descargar
los cambios al repositorio local.

**Archivos del repositorio:**
*README.md*: Tiene la descripción de la práctica, comandos de git con su descripción, procesos de creación de los repositorios, proceso de la vinculación y sincronización desde local -> GitHub y viceversa, descripción de los archivos y la conclusión personal.

*datos.txt*: Contiene los cambios que se realizaron desde la terminal y el repositorio de GitHub y para comprobar su sincronización.

## Conclusión personal

En esta práctica aprendí a manejar Git para llevar el control de las versiones de un proyecto. Tambien aprendí como modificar los docuemntos en en el repositorio local y en el repositorio de GitHub.