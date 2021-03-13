# proimpo
El proyecto proimpo2 se debera descargar el paquete .zip, luego descomprimir en paquete y guardar el programa en un interpretador de lenguaje de script como lo es xampp.
Una vez colocado en la carpeta localhost de xampp debera ingresar al proyecto.
colocamos a correr el xampp y activamos el apache y el mysql. 
Ahora vamos a cargar el sql, dando click en Admin de mrsql; este abrira la web de la DB. 
le damos click en importar, seleccionar archivo seleccionamos el sql donde lo tengamos descargado 
luego procedemos a ajustar unas cosas del proyecto para que pueda funcionar correctamente. 
Vamos a configurar el archivo de la DB. Colocamos los cambios necesarios por ejemplo si el xampp tiene un usuario o contraseña diferente al que esta en el proyecto. 
el archivo esta en la siguiente ruta. 
proimpo2/application/config/database.php 
A la siguiente ruta para poder modificar la ruta de ejecucion. Ruta: proimpo2/application/config/config.php estando en el archivo config.php modificamos  
el $config['base_url'] = 'aqui va la ruta de nuestro servidor local + el nombre del proyecto'; 
Con estos cambios el programa debe funcionar correctamente. 
