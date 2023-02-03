# Primer día con GIT Y GIT HUB


## Lista de comandos de git

* Para poder ver la version de git ejecutemos en nuestro terminal:


```bash 
git --version
git --v
```
* Para configurar el correo y nombre (sólo la primera vez en mi máquina)

```bash 
git config --global user.email "micorreo@gmail.com"
git config --global user.name "Mi nombre"
```
* Para ver la configuración de git

```bash
git config --list
```
* Sirve para inicializar GIT
```bash
git init
```
* Todas las carpetas que tengan un punto adelante significa que son carpetas ocultas.
```bash
.git
```
* Comit es hacer un registro de lo que hacemos de programación.
* Sirve para ver el estado actual con el estado que se va a realizar.
```bash
git status
git add .
git status
```
* Solo es para agregar especificamente por ejemplo:
```bash
git add README.md
```

* Para preparar nuestros archivos para la zona de stage (preparalos para commit)

```bash
git add .
```
* Creando el registro de los cambios realizados:
```bash
git commit -m "Creando mi primer commit"
```
* Verificando el git commit ver una linea de tiempo de los commits que hemos realizado:
```bash
git log
```
* Para ver el detalle especifico de un commit:
```bash
git show id-de-commit
```
* modificando