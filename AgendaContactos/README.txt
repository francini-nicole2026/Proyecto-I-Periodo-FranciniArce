
*PROYECTO: Sistema de contactos de salón de belleza*
------------------------------------------------------

Este proyecto es una aplicación web que hice con HTML, CSS, JS, Python y Flask.
Sirve para gestionar contactos de un salón de belleza principalmente creado para los dueños esto con el fin de que puedan llevar un orden de sus clientes, 
donde se pueden agregar, editar, eliminar y ver contactos.

También permite buscar personas, ordenarlas por nombre y ver un reporte general.
Además, los datos se guardan en un archivo Excel automáticamente.


*Requisitos para la buena ejecución*
------------------------------------

Para que el proyecto funcione se necesita tener instalado:

- Python 3
- Flask
- OpenPyXL


*Paso#1 Instalación de librerías*
---------------------------------

Antes de ejecutar el proyecto, hay que abrir una terminal y escribir:

pip install flask
pip install openpyxl

O también se puede instalar todo junto:

pip install flask openpyxl


*Paso a paso de como ejecutar el proyecto*
-----------------------------------------

Abrir la carpeta del proyecto en la terminal o en VS Code.

Ejecutar el archivo principal con este comando:
python app.py

Luego de ejecutarlo, aparecerá un enlace como este:
http://127.0.0.1:5000

Copiar ese enlace en el navegador para ver la página.


*Usuario y contraseña*
---------------------

Para iniciar sesión se usa:

Usuario: admin
Contraseña: 1234


*Archivos importantes*
-----------------------------------------

app.py → contiene todo el funcionamiento del sistema
templates/ → contiene las páginas HTML
static/ → contiene estilos CSS, imágenes y scripts
contactos.xlsx → archivo donde se guardan los contactos


*El sistema se encarga de:*
-----------------------------------------

Permite iniciar sesión
Agregar contactos nuevos
Editar contactos existentes
Eliminar contactos
Buscar contactos por nombre
Ordenar contactos
Ver detalles de cada contacto
Generar reportes
Guardar datos automáticamente en Excel