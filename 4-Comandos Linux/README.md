# <b> Comandos más usados en sistemas Linux </b>

<cite style="display:block; text-align: justify">Aunque muchas distribuciones de Linux incorporan modernos y avanzados GUI o interfaces gráficos, el máximo potencial de este sistema operativo se consigue tecleando comandos en la consola.

Es necesario conocer una serie de comandos Linux básicos para poder operar en este sistema operativo de forma más rápida y eficiente.

Desde la consola podemos ejecutar todo tipo de comandos y archivos, desde los más sencillos, a los más avanzados. Eso sí, esta terminal se suele utilizar para ejecutar todo aquello a lo que no tenemos acceso desde la interfaz gráfica del sistema operativo. </cite>

![Comandos](img_Comandos_Linux/img01.png)

# Comandos para la administración de archivos en Linux

# CD

<cite style="display:block; text-align: justify">Cd (de change directory o cambiar directorio), es como su nombre lo indica el comando que necesitarás para acceder a una ruta distinta de la que te encuentras. 

Por ejemplo, si estas en el directorio /home y deseas acceder a /home/ejercicios, seria:

    $ cd /home/ejercicios

Si estás en /home/ejercicios y deseas subir un nivel (es decir ir al directorio /home), ejecutas:

    $ cd …

![Comandos](img_Comandos_Linux/img02.png)
</cite>

# PWD

<cite style="display:block; text-align: justify">Pwd (de print working directory o imprimir directorio de trabajo), es un conveniente comando que imprime nuestra ruta o ubicación al momento de ejecutarlo, así evitamos perdernos si estamos trabajando con múltiples directorios y carpetas. Su sintaxis seria:

    $ pwd


![Comandos](img_Comandos_Linux/img03.png)
</cite>

# LS

<cite style="display:block; text-align: justify">Ls (de listar), permite listar el contenido de un directorio o fichero. La sintaxis es:

    $ ls /home/directorio

El comando ls tiene varias opciones que permiten organizar la salida, lo que resulta particularmente útil cuando es muy grande. Por ejemplo, puedes usar -a para mostrar los archivos ocultos y -l para mostrar los usuarios, permisos y la fecha de los archivos. Así como para todos los comandos Linux, estas opciones pueden combinarse, terminando en algo como:

    $ ls -la /home/directorio

![Comandos](img_Comandos_Linux/img04.png)
</cite>