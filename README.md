# gitlearn
Repositorio para laboratorio de Git 

## Instalación de GIT

Podemos instalar GIT (si no lo tenemos ya instalado): 

https://git-scm.com/download/win

Si tenemos Visual Studio o Visual Studio Code, seguramente ya tenemos instalado GIT.

## Usuario de github

Para poder hacer el laboratorio, es necesario tener una cuenta de github. Si no la tienes, puedes crearla en el siguiente enlace: https://github.com/join

## Instalación de Visual Studio o Visual Studio Code

Para poder hacer el laboratorio, es necesario tener instalado Visual Studio o Visual Studio Code. Si no lo tienes, puedes descargarlo en el siguiente enlace: https://code.visualstudio.com/

### Extensiones de Visual Studio Code

Para poder hacer el laboratorio, es necesario tener instaladas las siguientes extensiones de Visual Studio Code:

- GitHub.remotehub 

Esto nos facilitará la gestión de credenciales de github y no tendremos que gestionarlo nosotros.


## Clonar repositorio

Para clonar un repositorio, se debe ejecutar el siguiente comando:

```bash
git clone https://github.com/gperezivo/gitlearn.git
```

Si usamos Visual Studio Code, podemos clonar el repositorio desde la interfaz de Visual Studio Code.
Abrimos la opción de Source Control y pulsamos en el botón de Clone Repository o bien pulsamos Ctrl+Shift+P y escribimos "Clone Repository".


## Pasos del laboratorio

### 1. Clona el repositorio
### 2. Crear una rama a partir de la rama main. 
   > git checkout -b <nombre_rama>

   Como nombre de la rama vamos a usar el siguiente formato `feature/<nombre_usuario>`

   
   
### 3. Crear ficheros nuevos

Generar un fichero .txt con el nombre de la rama que se ha creado y escribir en el fichero el nombre del usuario que ha creado la rama.

### 4. Modificar ficheros existentes

Modificar el fichero doc/README.md y añadir el nombre del usuario que ha creado la rama.

### 5. Hacer dos commits diferentes:

- El primero con el mensaje "Añadido fichero <nombre_rama>.txt". Debe incluir solo el fichero creado en el paso 3.
- El segundo con el mensaje "Añadido usuario <nombre_usuario> a la lista de ramas". Debe incluir solo el fichero modificado en el paso 4.

### 6. Hacer un push de la rama al repositorio remoto

Subir la rama al repositorio remoto.

### 7. Crear un pull request

Crear en github un pull request para que se haga el merge de la rama en la rama main.

Después de que de conflicto, tenemos que traer los cambios de la rama main a la rama de trabajo y resolver los conflictos.
Lo podemos hacer con el siguiente comando:

```bash
git pull origin main
```


Entonces podremos subir los cambios y continuar con el pull request.


