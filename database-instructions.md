# Base de datos (DB)

Yo voy a utilizar el motor de DB PostgreSQL, a continuación dejo las instrucciónes para crear la DB para resolver los ejercicios.  
 
Una vez instalado PostgreSQL y pgAdmin vamos a crear la estructura de datos. En los archivos platzi-carreras.sql y platzi-alumnos.sql se encuentra el código SQL para hacerlo.  
Primero se crea una Base de datos, luego dar click derecho en la sección Schemas, y en Create -> Schema.  
Al seleccionar la opción abrirá un cuadro de diálogo en donde debes escribir el nombre del esquema, en este caso será “platzi”. Selecciona tu usuario de postgres en el campo Owner, esto es para que asigne todos los permisos del nuevo esquema a tu usuario.  
 
Dirígete al menú superior y selecciona el menú Tools > Query Tool. 
Esto desplegará la herramienta en la ventana principal. Da click en el botón “Open File” ilustrado por un icono de folder abierto.  
Previamente debes descargar los archivos **platzi-carreras.sql** y **platzi-alumnos.sql**, para poder seleccionarlos. En caso de no descargar los archivos, puedes copiar y pegar el código en la ventana Query Tool. Es importante que primero ejecutes el código del archivo platzi-alumnos.sql  
Para ejecutar el código, debes seleccionarlo todo (con **Ctrl + A** en Windows) y presionar en el ícono de play.  
Realizar el mismo proceso con **platzi-carreras.sql** 