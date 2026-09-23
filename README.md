## Pregunta 1

### Diferencias conceptuales

**git clone:** Permite copiar un repositorio remoto a mi computadora para
trabajar con sus archivos y su historial de versiones.

**fork:** Permite crear una copia de un repositorio ajeno dentro de mi cuenta
de GitHub para trabajar sobre él sin modificar directamente el repositorio
original.

**git pull:** Permite obtener los cambios más recientes del repositorio remoto
e integrarlos en mi rama local.

### Parte práctica

**¿Cómo se realizó el fork?**

Ingresé al repositorio proporcionado, presioné el botón Fork y creé una copia
del repositorio en mi cuenta personal de GitHub.

**¿Cómo se realizó el clone del fork?**

Ingresé a mi fork, copié la URL del repositorio y ejecuté:

git clone URL_DEL_REPOSITORIO

**¿Cómo se verificó que se estaba trabajando sobre el fork?**

Ejecuté el comando:

git remote -v

Se comprobó que origin apuntaba al repositorio de mi cuenta dario20-13 y no
al repositorio original.