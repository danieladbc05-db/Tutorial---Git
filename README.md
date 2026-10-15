Tutorial---Git

Actividad 2 - Introducción Ciencia de Datos

Curso Ciencia de Datos - Uniagraia

Estudiante: Shalom Daniela Baquero Castrillón

PROCESO

1. Creé una cuenta en GitHub.
2. Verifiqué que Git estaba instalado en macOS con git --version.
3. Configuré mi nombre y mi correo:
   - git config --global user.name "[Tu nombre]"
   - git config --global user.email "[tu correo]"
4. Generé un token de acceso personal en GitHub, necesario para autenticarme al hacer `git push` desde la Terminal.

Después:

1. Creé el repositorio Tutorial-Git en GitHub, con un archivo README.
2. Lo cloné en mi computador con git clone https://github.com/danieladbc05-db/Tutorial---Git.git.
3. Elaboré tres documentos de Word con un tutorial de Git, y exporté cada uno a PDF.
4. Por cada capítulo repetí este ciclo:
   - git status para ver los archivos nuevos.
   - git add . para preparar los cambios.
   - git commit -m para confirmarlos con una descripción.
   - git push para enviarlos a GitHub.
  
Agregué los Capítulos 1, 2 y 3, en Word y PDF.

DIFICULTADES

- No pude crear el token por falta de acceso al correo de mi primera cuenta, así que creé una cuenta nueva de GitHub con un correo al que sí tenía acceso, un repositorio nuevo, y repetí la configuración y el clonado.
- Se subieron archivos temporales de Word (~$...). Los eliminé del repositorio con git rm --cached.
- El git push fallaba con "Authentication failed". El token no era válido, generé uno nuevo con el permiso repo y funcionó.
  
