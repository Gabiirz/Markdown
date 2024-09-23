# Guía Práctica de GitHub 

## Autor
**Gabriel Rezende**

## Introducción
GitHub es una plataforma de desarrollo colaborativo para alojar proyectos utilizando el sistema de control de versiones Git. Es ampliamente utilizada por desarrolladores para gestionar proyectos, colaborar en equipo y realizar un seguimiento del progreso del código. En este informe, se detallarán algunas de las funcionalidades básicas de GitHub, así como los pasos a seguir para realizarlas.

## Funcionalidades y Pasos a Seguir

### 1. Crear un Repositorio.
  Para crear un repositorio en GitHub:
  1. Inicia sesión en tu cuenta de GitHub.
  2. Haz clic en el botón `New` en la parte superior derecha.
  3. Introduce un nombre para el repositorio.
  4. Añade una descripción opcional.
  5. Selecciona la visibilidad: `Public` o `Private`.
  6. Haz clic en `Create repository`.

### 2. Clonar un Repositorio.
  Para clonar un repositorio en tu máquina local:
  1. Navega al repositorio que deseas clonar.
  2. Haz clic en el botón `Code`.
  3. Copia la URL del repositorio.
  4. Abre tu terminal y escribe:
  ```bash
     git clone URL_DEL_REPOSITORIO
  ```


### 3. Hacer Cambios en tu Repositorio.
  Para hacer cambios en tu repositorio local:
  1. Navega al directorio del repositorio clonado en tu terminal.
  2. Realiza los cambios que desees en los archivos.
  3. Guarda los cambios en los archivos.

### 4. Añadir cambios.
  Para preparar tus cambios antes de hacer un commit:
  ```bash
    git add .
  ```

### 5. Hacer un Commit.
  ```bash
    git commit -m "Descripción de los cambios".
  ```


### 6. Sincronizar Cambios con el Repositorio.
  ```bash
    git push origin main.
  ```







