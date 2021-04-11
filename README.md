# Tutorial para ejecutar Jupyter en Windows

Para este tutorial se asume que ya está instalado Python y Jupyter en el computador.

## Parte 1 Comprobar la instalación de Jupyter
Algunas instalaciones actualizan la variable de entorno `path`, permitiendo ejecutar Jupyter directamente. En otros casos es necesario actualizar la variable de entorno, lo cual se explica en la pare 2 de este documento.

Una forma para saber si la variable de entorno esta actualizada es intentando ejecutar Jupyter en la ventana de comandos de Windows. Lo primero es abrir la ventana de comandos
 ![Abrir_CMD](https://github.com/GerardoMunoz/Ejecutar_Jupyter_Windows/raw/main/Abrir_CMD.png)

### Variable de entorno `path` actualizada 
Si la variable de entorno esta actualizada, se ve de la siguiente forma luego de introducir `jupyter`.

![CMD_Jupyter_si](https://github.com/GerardoMunoz/Ejecutar_Jupyter_Windows/raw/main/CMD_Jupyter_si.png)

En este caso puede pasar directamente a la parte 3.


### Variable de entorno `path` no está actualizada 
Si la variable de entorno no está actualizada se ve de la siguiente forma luego de introducir `jupyter`.

![CMD_Jupyter_si](https://github.com/GerardoMunoz/Ejecutar_Jupyter_Windows/raw/main/CMD_Jupyter_si.png)

Para actualizarla debe seguir los pasos de la parte 2.

## Parte 2 Encontrar jupyter
En la siguiente imagen se ilustra como yo encontré la dirección de Jupyter en mi disco duro introduciendo el comando `dir jupyter.exe /s`.

![buscar_jupyter](https://github.com/GerardoMunoz/Ejecutar_Jupyter_Windows/raw/main/buscar_jupyter.png)

Luego debe adicionar esa dirección en la variable de entorno `path`

## Parte 3 Crear el acceso directo

En las siguientes imágenes se ilustra como crear el acceso directo.

![crea_acceso_directo](https://github.com/GerardoMunoz/Ejecutar_Jupyter_Windows/raw/main/crea_acceso_directo.png)

![acceso_directo_paso1](https://github.com/GerardoMunoz/Ejecutar_Jupyter_Windows/raw/main/acceso_directo_paso1.png)

![acceso_directo_paso2](https://github.com/GerardoMunoz/Ejecutar_Jupyter_Windows/raw/main/acceso_directo_paso2.png)

![acceso_directo_paso3](https://github.com/GerardoMunoz/Ejecutar_Jupyter_Windows/raw/main/acceso_directo_paso3.png)

En el primer campo adiciona el texto ` notebook --notebook-dir=C:\`

En el siguiente campo sólo deja `C:\`

![acceso_directo_paso4](https://github.com/GerardoMunoz/Ejecutar_Jupyter_Windows/raw/main/acceso_directo_paso4.png)
