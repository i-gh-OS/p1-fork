# COMANDOS BÁSICOS:

## git clone
### Significado
Crea copia local de repositorio remoto en mi ordenador.

### Utilidad
Para trabajar en modo local con el codigo del repositorio.

### Funcionamiento interno
* Descarga todos los archivos
* Descarga el historial de commits
* Configura automáticamente el remoto ``origin`` apuntando al fork

---

## git status
### Significado
Muestra el estado actual del repositorio local.

### Utilidad
Para saber:
* En qué rama estás
* Qué archivos has modificado
* Qué archivos están preparados para commit
* Si tienes commits pendientes de subir

---

## git add
### Significado
Añade archivos al área de preparación (staging area) antes de que vayan al próximo commit.

### Utilidad
Para decidir que cambios individuales quiero que se empaqueten en el commit siguiente y cuales no.

### Funcionamiento interno
El archivo pasa de “modificado” a “staged”

---

## git comit
### Significado
Guarda los cambios preparados (git add) en el historial del repositorio local.
Aquí todavía no se sube nada a GitHub, el commit es local.

### Utilidad
Para crear un punto del historial con:
* Autor
* Fecha
* Mensaje descriptivo
y seguir un orden de los cambios realizados. 

---

## git push
### Significado
Envía los commits locales al repositorio remoto (origin).

### Utilidad
Ver los cambios en el repositorio de GitHub en la nube. Es útil tenerlo en la nube para acceder a los cambios desde cualquier sitio cuando no tenemos el ordenador con los cambios locales.

### Funcionamiento interno
* Sube los commits que no existían en el remoto
* Actualiza la rama remota

---

## git checkout
### Significado
Crea ramas nuevas, cambia a ellas o restaura archivos.

### Utilidad
Para tener ramas diferenciadas por personas o versiones antes de la versión estable.
